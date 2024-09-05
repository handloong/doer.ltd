# POM

全称Project Object Model, maven的管理包的工具,简单类比为 node 的npm, C#的nuget, go 的cargo等.

> maven简称mvn

打开项目创建的默认POM文件

```
<modelVersion>4.0.0</modelVersion>
```

这个我也不知道是啥,可能是mvn的版本吧

```xml
<groupId>com.sp2learn</groupId>
<artifactId>L01</artifactId>
<version>1.0-SNAPSHOT</version>
```

这三个标签定义了项目的```坐标```，这是Maven用来唯一标识一个构件（如JAR文件）的方式：

* `groupId`通常是公司的反向域名或组织名称。
* `artifactId`是项目的名称。
* `version`是项目的版本号，这里的`SNAPSHOT`表示这是一个开发中的版本，不是稳定版

坐标简单解释: maven通过一些规则来定位一个包.相当于现实生活中的经纬度一样.

```
<properties>
    <maven.compiler.source>8</maven.compiler.source>
    <maven.compiler.target>8</maven.compiler.target>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
</properties>
```

`properties`元素包含了一系列键值对，用于配置Maven的行为和其他插件可能用到的属性：

* `maven.compiler.source`和`maven.compiler.target`定义了编译Java源代码的目标JDK版本，在这里是Java 8。
* `project.build.sourceEncoding`指定了源代码的字符编码，这里是UTF-8。
