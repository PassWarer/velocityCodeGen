# VelocityCodeGen 代码自动生成工具
---
使用velocity对Model生成对应的action及dao文件，相关配置需要自己填写。下一步是使用xjavadoc和javaparser读取实体类的内容，从中解析出javadoc的注释，以及annotation内容，然后完成对应属性设置，以实现全自动的文件生成。

---
增加对文件某一文件夹下的POJO类进行扫描与解析（利用xjavadoc与parser）,完成属性的自动设置。目前action及dao模板并不能直接用于生产环境的，只是做一个简单的示例。可以根据自己公司的情况完成velocity模板的编写。下一步考虑对简单的配置文件的生成。