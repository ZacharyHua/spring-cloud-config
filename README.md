# spring-cloud-config

- 测试
  1. 可以让配置中心直接从github上拉取配置文件
  2. 拉取的配置文件必须在分支的主目录下（没有测试分支）


- 在使用配置中心的时候我们需要引入一个config-client的jar
```jar
        <dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-config-client</artifactId>
        </dependency>
```
