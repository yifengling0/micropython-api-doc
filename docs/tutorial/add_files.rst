.. _tutorial_micropython_add_files:

程小奔添加自定义类库
======================================

版权声明：翻译整理属于makeblock，转载时请以超链接形式标明文章原始出处和作者信息及本声明

将自己编写的一些Python脚本的类库添加到固件中，在使用时只需import调用，就像使用内置的python库一样简单便捷;
同时还有另外一个重要的功能，就是可以很好的保护源代码。比起生成mpy加密文件这种方式来说，显式添加到固件中会更加安全可靠。