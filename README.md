# VelocityCodeGen
---
代码自动生成工具

使用velocity对Model生成对应的action及dao文件，相关配置需要自己填写。下一步是使用xjavadoc和javaparser读取实体类的内容，从中解析出javadoc的注释，以及annotation内容，然后完成对应属性设置，以实现全自动的文件生成。