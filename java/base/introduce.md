
Java语言的特点
面向对象性
  两个要素: 类  对象
  三个特征: 封装 继承 多态
健壮性
  1.去除了C语言的指针
  2.自动的垃圾回收机制。 仍然会出现内存溢出 内存泄漏

跨平台行: writ once,run anywhere   (JVM)


Java的两种核心机制 
 Java 虚拟机 (Java Virtal Machine)
 垃圾回收机制(Garbage Collection)


JDK (Java Development Kit   Java开发工具包)
  JDK是提供给Java开发人员使用的，其中包含了Java的开发工具，也包含了JRE。所以安装了JDK，就不用单独安装JRE了。  其中的开发工具: 编译工具javac.exe 打包工具jar.exe等

JRE(Java Runtime Environment Java运行环境)
  包括Java虚拟机(JVM Java Virtual Machine)和Java程序所需的核心类库等,如果想要运行一个开发好的java程序，计算机只需要安装JRE即可。 

简单来说，使用JDK的开发工具完成Java程序，交给JRE去运行。
JDK = JRE+开发工具集(例如javac编译工具等)
JRE = JVM+ Java SE标准类库



java注释
java规范了三种注释方式
  单行注释. // 
  多行注释.  /*   */
  文档注释(java特有)
    格式: /**
          @author 指定java程序的作者
          @version 指定源文件的版本
          */
    特点:注释内容可以被JDK提供的工具 javadoc所解析,生成一套以网页形式体现的该程序的说明文档。 
    操作方式： javadoc -d mydoc -author -version HelloWorld.java
特点: 单/多行注释不参与编译. 


API (Application Programming Interface 应用程序编程接口) 是Java提供的基本编程接口。 
IDE (Integrated Development Environment) 集成开发环境


一个java源文件中可以声明多个class.但是，最多只能有一个类声明为public的,且要求文件名跟public类同名。 
程序的入口是main()方法。 格式是固定的。 


Java中严格区分大小写
