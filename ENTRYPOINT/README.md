### Entry point

Entrypoint is also used to run the container just like CMD, but there are few differences.
1.We can't override entry point , we can override command
2.We can't overridr thr entry point, if you try to do it will go and append to the ENTRYPOINT command.
3.if we use cmd and entry point, don't give any command from terminal cmd acts as argument provider to ENRTYPOINT
4.CMD will supply default arguments to NETRYPOINT
5.You can always override CMD arguments from runtime.
6.You can stop misusing your image with other commands.