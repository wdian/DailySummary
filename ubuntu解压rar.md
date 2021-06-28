# ubuntu解压rar压缩文件（7z）

## 尝试采用rar解压

终端中输入命令安装压缩程序rar和解压缩的unrar.

```
sudo apt-get install rar unrar
sudo apt-get install rar rar
```

linux中解压rar类型文件的命令为：
 unrar  e file.rar  # 把原rar压缩包中的全部文件解压到当前目录下
 rar x file.rar  # 把原rar压缩包中的全部文件解压到x下

**但是没有成功**

报错信息为：

```
unknown archive type, only plain RAR 2.0 supported(normal and solid archives), SFX and Volumes are NOT supported!
```

## 7z解压rar文件

```
sudo apt -get install p7zip-full
```

解压：

```
7z x file.rar
```

