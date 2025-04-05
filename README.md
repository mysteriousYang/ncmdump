# NCM文件转换器

可以将网易云会员下载的.ncm文件转换为.mp3或.flac

## 使用方法

将需要转换的NCM文件全部放入该py文件所在目录

运行**ncmdump.py**，会自动将转码结果存放在 .\unlock 下

若没有安装Crypto库，则请安装以下库

```shell
pip install pycryptodome
```