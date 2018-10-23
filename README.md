# SSM 种子项目(Maven)
导入项目以后使用eclipse打开即可
----

* 修改项目名称
* src/main/resources/db.properties
	* jdbc.username= 
	* jdbc.password=
	* jdbc.url=  其中数库的名称  
* src/main/resources/log4j.properties
	* log4j.appender.File.File =  log文件存放的位置及名称
* **删除不必要的文件**
	1. src/main/resource/mappers-> DemoMapper.xml 如果mappers为空会报错，所以添加了一个空的mapper文件，开发中记得删除此文件（mappers文件夹有其他文件后）
	2. src/main/java/cn/edu/hdu/zhn -> DemoDao.java 为了配合DemoMapper文件不报错 而添加的 

