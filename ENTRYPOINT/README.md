### Entry point

Entrypoint is also used to run the container just like CMD, but there are few differences.
1.We can't override entry point , we can override command
2.We can't overridr thr entry point, if you try to do it will go and append to the ENTRYPOINT command.