# sissy university 移动课程中心

sissy university 移动课程中心。来自`抖喵家`的在线XXXX和XXX的单机游戏安卓移植本地版本。

没有任何网络请求权限，隐私万岁。

## Build

你需要一份原版的sissy university数据副本来构建该软件。你可以从原网站下载或从TG群组下载由Star依原网站进行封装的桌面版。

请将`css`,`js`,`img`目录拷贝到`app/src/main/assets/public`目录下，注意，请勿覆盖`app/src/main/assets/public/index.html`。

构建前你可能需要创建自己的签名证书，详情请见`app/build.gradle`。

## Use

您可以直接到[Release](https://github.com/leegggg/sissy-univ-android/releases)里面寻找最新的版本。

本版本的存档文件与网页版和PC版兼容。

该App会请求本地存储权限用于数据导出，禁止该权限不影响其他功能。

导出记录文件位于设备默认下载目录，一般为`/storage/emulated/0/Download/`。

导出记录文件后会自动打开分享页面，可以在此页面将保存的记录通过其他app发送。

发现BUG请在此Repo提交Issue或PR。
