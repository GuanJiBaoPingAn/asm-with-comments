在class 文件被JVM 装载后，会对类文件进行校验，检查内容如下。
+ 开始四字节的魔数正确
+ 所有被识别的属性必须在合理长度下
+ 类文件不能被修改或在结尾有额外字节
+ 常量池必须满足限制
+ 常量池中的所有域引用和方法引用必须有有效的名称、有效的类、有效的描述符

