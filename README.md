# Mybatis_Generate_project01
mybatis代码生成器提交2022-11-14

使用说明：
1.生成代码之前删除mapper和pojo两个目录下的文件。
2.修改generateonfig.xml中的table标签的两个属性，tableName是数据库表的名称（想生成哪个就写哪个），domainObjectName是实体类的名称。
3.记得修改jdbcConnection标签的数据库连接到参数。
针对mysql8的版本，建议URL跟上参数
?useSSL=false&amp;useUnicode=true&amp;characterEncoding=UTF-8&amp;serverTimezone=Asia/Shanghai&amp;allowPublicKeyRetrieval=true
驱动是：com.mysql.cj.jdbc.Driver（xml配置文件中已写好）
当然你也可以写一个数据库连接的properties文件来读取。
