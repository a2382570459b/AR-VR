## Unity安装
Unity的软件去可以去[官网](https://store.unity.com/download-nuo)下载安装。
除此之外我还安装了**UnitySetup-Android-Support-for-Editor-5.6.2f1**也就是安装支持包和**UnityStandardAssetsSetup-5.6.2f1**需要注意的是后者在安装时需要安装到和Unity不同的文件夹中，不然Unity你会一直打不开，而后者可以直接安装到Unity所在的文件夹中，不然安装不了。

## java开发平台安装
具体安装教程可以参考[https://www.cnblogs.com/maoning/p/10701349.html](https://www.cnblogs.com/maoning/p/10701349.html)内有软件安装地址。

##### 下面说一下过程中需要注意的事项：
先要进行环境变量的设置。

- 右键我的电脑打开属性。
![d5de6fe706c7b9d76080b0a6bf47995.png](https://upload-images.jianshu.io/upload_images/9860856-3254c50c02bbca06.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 点击高级系统设置后再点击环境变量

![7eb51b80532e4ce16c501c8281ca3d1.png](https://upload-images.jianshu.io/upload_images/9860856-5aa24ab3a68de1de.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

最后在用户变量那框新建如下图所示的变量，注意**变量值必须全英文**，而且变量值就是你等等要将java安装的位置。

![7d63e357e74acacf3bffd19270ed013.png](https://upload-images.jianshu.io/upload_images/9860856-c7c9b388a0ec6b04.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

确定好之后进行软件安装，安装到变量值所写位置。
安装好后，去CMD窗口输入“java- -version”看看是否安装成功，成功了的话会显示java版本。

## 安装安卓开发平台
安装sdk开发包。这里指需要注意一点，为了后面配置unity时不出现错误，一定要安装到**全英文路径**下！
其他不做过多赘述。

## 配置unity的安卓运行环境
打开unity创建新项目，打开项目。
进入到项目页面后操作如下图。

![f0fcc5f807d5558e953bf448b2272a9.png](https://upload-images.jianshu.io/upload_images/9860856-da396616c77f567c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![b4fa94f699e97003b21df3b1553559a.png](https://upload-images.jianshu.io/upload_images/9860856-b80c12b4d2c55e4e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

注意下面的SDK就是我们刚刚安装的位置，JDK也是jdk安装的位置，设置好这两个就行了，如果这两个链接为中文，那么后续发布文件时会出现错误。

然后就是在file的builtsetting，进行安卓的选择，然后就是一些设置（这里网上很多教程就不说了）。最后成功发布。

![bdf1e448db10914e2d61dd4246d7605.png](https://upload-images.jianshu.io/upload_images/9860856-4910f1f50bd12cee.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![6a91700df6f9e992284187de513a8a4.png](https://upload-images.jianshu.io/upload_images/9860856-b6ff06ecf519d5fa.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

