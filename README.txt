java程序： 1.创建工程 mvn archetype:generate 2.编译工程 mvn clean complie 3.执行 mvn exec:java -Dexec.mainClass="com.hand.App" -Dexec.args="arg0 arg1 arg2"

web程序： 1.创建工程 mvn archetype:generate 2.编译工程 mvn clean complie 3.执行 mvn jetty:run