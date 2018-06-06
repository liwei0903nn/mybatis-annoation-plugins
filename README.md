# mybatis dao层注解、mapper、domain生成工具
## 1.说明
```$xslt
mybatis-annotation-plugins是一款mybatis注解生成工具，主要用于产生mybatis的model、mapper、dao层文件
```

## 2. 引用pulgins文件
```$xslt
<plugin>
 <groupId>edu.whu</groupId>
 <artifactId>mybatis-annotation-plugins</artifactId>
  <version>1.2</version>
</plugin>
```

## 3.添加配置文件
```$xslt

database:
 driver: com.mysql.jdbc.Driver
 url: example
 username: root
 password: passs

package:
 model: com.model
 dao: com.dao
 mapper: com.mapper

tables:
 table1:
  name: table
  enableDelete: false
 table2:
  name: table
```