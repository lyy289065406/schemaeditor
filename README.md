# schemaeditor

> swing 绘图构件

------

## 简介

因此构件的官方组织/作者已放弃维护，且在 maven 中央仓库无法下载原版，故有了此项目。


## 使用方式

maven 的 `settings.yml` 配置 sonatype 中央仓库：

```xml
<mirror>
    <id>mvnrepository</id>
    <mirrorOf>mvnrepository</mirrorOf>
    <url>http://mvnrepository.com/</url>
</mirror>

<mirror>
    <id>sonatype</id>
    <mirrorOf>sonatype</mirrorOf>
    <url>https://s01.oss.sonatype.org/</url>
</mirror>
```

项目的 `pom.xml` 配置构件坐标：

```xml
<dependency>
    <groupId>com.exp-blog</groupId>
    <artifactId>schemaeditor</artifactId>
    <version>1.0.0</version>
</dependency>
```
