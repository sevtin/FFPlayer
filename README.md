# FFPlayer
MacOS FFPlayer

https://trac.ffmpeg.org/wiki/CompilationGuide/macOS

1.添加ffmpeg相关头文件的路径：点击项目，Build Settings——>Search Paths——>Header Search Paths中加入/usr/local/opt/ffmpeg/include

2.添加ffmpeg相关库文件的寻找路径：点击项目，Build Settings——>Library Search Paths中加入/usr/local/opt/ffmpeg/lib。

3.添加ffmpeg link的library：点击项目，Build Phases——>Link Binary With Libraries——>Add Others——>cmd+shift+G——>选择/usr/local/opt/ffmpeg/lib下的Developers下的所有dylib库
