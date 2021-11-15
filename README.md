# Tremux Aria2 配置

此项目是根据 **[Aria2 完美配置](https://github.com/P3TERX/aria2.conf)** 项目进行对 **Ternux** 端的适配。

**Aria2 完美配置**项目地址: [https://github.com/P3TERX/aria2.conf](https://github.com/P3TERX/aria2.conf)

## 使用说明

首选安装aira2

```
pkg install aria2
```

将`.aria2c`与`start_aria2.sh`复制到：

```
/data/data/com.termux/files/home/
```

修改 `.aria2c/aria2.conf` 下载的路径，例如：

```
dir=/data/data/com.termux/files/home/downloads
```


