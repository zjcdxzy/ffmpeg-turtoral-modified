**重新写了一个是因为官网上的ffmpeg的demo在现在新版本下已经不能编译了。**   
所以就修改一下，顺便加点注释，重新学习下。  
ffmpeg-turtoral-modified  
**ffmpeg sdl2**  
######这是原先的：  
https://github.com/mpenkov/ffmpeg-tutorial  
http://dranger.com/ffmpeg/  


*我用的是xcode7编译的。  
*昨天（2016_05_27），我用vs编译了一下，发现问题有很多，很多编译错误（很多接口、数据类型被抛弃了，但是奇怪的是xcode下能编译，vs2013就不行了），我就不研究了（我研究了一下发现有的数据类型明明说了被抛弃了，但是新添加的接口还在用这些类型，然后我就迷茫了）。  后来发现，是我错了，下载的是最新的ffmpeg库，而不是稳定版的。稳定版的就正常了，没有这些奇怪的错误了。  
*我现在用的版本是 sld是2.0.4，ffmpeg是ffmpeg-3.0.2.tar.bz2  

### xcode加载の库:lollipop: 
<img src="xcode_load_libs.png" style="width: 600px;"/>

- ffmpeg的文档比sdl2差远了。
- ffmpeg现在的接口变化有点大，我都有点吃力了。
- 新的东西总是有这样或者那样的问题，如果可以还是用老的稳定的版本，不然出错了都不知道该找谁。



----------


1. My QQ: 2118977085  
2. e-mail：ziyi.001@163.com

**5/27/2016 11:59:25 AM**