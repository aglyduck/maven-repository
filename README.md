# maven-repository
## 引用Maven库
本Maven库的URL地址如下：
https://raw.github.com/aglyduck/maven-repository/master

    <repository>
        <id>net.iglyduck.maven-repository</id>
        <name>Aglyduck's Maven Repository</name>
        <url>https://raw.github.com/aglyduck/maven-repository/master</url>
    </repository>

本Maven库的内容包括：

## SQLServer JDBC Library
针对JDBC 4.2的引用：

    <dependency>
        <groupId>com.microsoft</groupId>
        <artifactId>sqljdbc42</artifactId>
        <version>6.0.6629.101</version>
    </dependency>

针对JDBC 4.1的引用：

    <dependency>
        <groupId>com.microsoft</groupId>
        <artifactId>sqljdbc41</artifactId>
        <version>6.0.6629.101</version>
    </dependency>
    
针对JDBC 4.0的引用：

    <dependency>
        <groupId>com.microsoft</groupId>
        <artifactId>sqljdbc4</artifactId>
        <version>6.0.6629.101</version>
    </dependency>
    
针对JDBC 3.0的引用：

    <dependency>
        <groupId>com.microsoft</groupId>
        <artifactId>sqljdbc</artifactId>
        <version>6.0.6629.101</version>
    </dependency>
    
此SQLServer JDBC Library使用下面的类作为JDBC Driver

    com.microsoft.sqlserver.jdbc.SQLServerDriver

## DB2 JDBC Library
针对DB2 10.5 JDBC 4.0的引用：

    <dependency>
        <groupId>com.ibm</groupId>
        <artifactId>db2jcc4</artifactId>
        <version>4.19</version>
    </dependency>

针对DB2 10.5 JDBC 3.0的引用：

    <dependency>
        <groupId>com.ibm</groupId>
        <artifactId>db2jcc</artifactId>
        <version>3.69</version>
    </dependency>
    
此DB2 JDBC Library使用下面的类作为JDBC Driver

    com.ibm.db2.jcc.DB2Driver
