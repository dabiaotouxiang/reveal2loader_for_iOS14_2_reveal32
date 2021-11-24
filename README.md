## Reveal2Loader-iOS14-reveal32

[Source Code](https://github.com/eziochiu/Reveal2Loader-Fixed-on-iOS12)

安装方法
```
1. cd 到工程目录reveal2Loader文件夹下 执行下列语句

find . -name .DS_Store -print0 | xargs -0 git rm -f –ignore-unmatch 删除当前目录的DS_Store隐藏文件

sudo dpkg-deb -b Package reveal2Loader.deb (前提是必须安装dpkg，可以用brew安装也可以用macport安装)

然后会在目录下生成reveal2Loader.deb

2、将reveal2Loader.deb拷贝到手机

3、将原来的reveal2Loader插件卸载，注销SpringBoard

4、直接用filza找到该文件进行安装，前提是卸载之前的旧版本，否则会报错。
```

参考 http://eziochiu.cn/2020/09/14/iOS%20Reveal2Loader%E4%BF%AE%E5%A4%8D%E7%89%88%EF%BC%88iOS13%E4%BF%AE%E5%A4%8D%EF%BC%89/

我仅仅是将reveal的framework修改为32版本的重新打包安装