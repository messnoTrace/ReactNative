# ReactNative
ReactNative 初体验

1.JDK环境变量配置
2.Android SDK环境变量配置
3.Node.JS    
 [点这里](http://nodejs.cn/)下载，大家可以通过node -v命令来测试有没有安装成功    
4.安装react-native-cli      

      npm install -g react-native-cli



###项目创建、编译、运行   
1.项目创建     

     react-native init XXXX      XXXX为项目名
>PS:init项目的时候，会卡很久才能初始化完成，另外，此条在CMD窗口中执行命令的时候不要切换文件夹，可能会出错。（想要切换project目录等下载好后，将node_modules文件夹压缩，然后删除，然后再copy到指定文件夹，不然会报文件夹名字过长巴拉巴拉的）   

2.项目调试运行
  win+R 打开cmd窗口，cd到项目目录下
先运行 react-native start 启动服务     
   
          react-native start

再打开新的cmd窗口，进入项目目录 react-native run-android     

        react-native run-android
