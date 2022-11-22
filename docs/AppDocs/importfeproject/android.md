## 导入资源

将app资源拷贝到项目assets->apps下，目录结构如下图

![avatar](https://img.cdn.aliyun.dcloud.net.cn/nativedocs/5%2BSDK-android/image/5-8.png)

## 配置应用信息

修改dcloud_control.xml中的appid为uni-app的id，确保dcloud_control.xml中的appid与manifest.json中的id与文件夹名一致，如下图所示：
		
![avatar](https://img.cdn.aliyun.dcloud.net.cn/nativedocs/5%2BSDK-android/image/5-9.png)

## 内置资源更新

如果您更新了内置资源，重新运行App加载的还是旧的资源时请检查下面的配置：

1. 内置的资源版本名称和版本号需要高于上一个版本；

## 编译运行

项目配置完成，直接点击android studio运行按钮即可。