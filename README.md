# WinZip
破解 WinZip.apk 方法

=================

应用名称：WinZip.apk

应用包名：com.winzip.android

备注：此应用需通过 应用内购 升级Pro版

破解方法：

① 首先，反编译 WinZip.apk，然后反编译 classes.dex。

② 找到 com/winzip/android/WinZipApplication.smali 文件并打开，定位到如下代码：

	.method public onCreate()V
    .registers 9

    .prologue
    const/4 v7, 0x1

    const/4 v6, 0x0   //将 0x0 修改为 0x1

    .line 85
    invoke-super {p0}, Landroid/app/Application;->onCreate()V


按照上述标注修改然后保存。

最后编译→安装即可 。破解完毕！

=================

【特别声明】

👉 不保证上述破解方法永久有效！ 
如果此应用开发者重新修改代码，那上述破解方法就失效！这你必须要清楚明白！

👉 开发者敲字母编写程序代码也不容易，如果你条件(不管是经济还是网络条件)允许，还是请通过 Google Play商店 支付美元购买原版APK应用！以支持开发者的开发工作。

👉 我破解是因为我没有上述那个条件。穷逼无美元的破解者一个。 如果你愿意，请捐赠以支持我的破解工作。

👉 如果你还有问题？请 <a href=https://github.com/APK-Patched/WinZip/issues>在此</a> 提交你的问题。
