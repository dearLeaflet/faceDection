1、在vs项目属性中添加包含目录：配置属性 -> VC++目录 -> 包含目录  Dlib
2、在属性添加预处理 C/C++ -> 预处理器 -> 预处理器定义 添加 DLIB_JPEG_SUPPORT
3、将根目录下 external中的 libjpeg文件夹下的文件添加到项目工程中