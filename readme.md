这里分2种方式，
1.  java –javaagent:agent.jar 前置代理，当个jvm项目。这里我没办法抽象出来。
JRebel插件的实现原理。
https://www.cnblogs.com/freemanabc/p/5618180.html
https://cloud.tencent.com/developer/ask/104568
2. VirtualMachineDescriptor 这个只能代理，之前所有jvm启动的项目。再它之后的项目不生效 

- win:
    run.bat就行。
- linux:
    sh run.sh