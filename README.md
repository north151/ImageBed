# ImageBed
**This is the imagebed1.**


## For Linux

1.选择 PicGo-Core(command line)

2.点击  "下载或更新"

（Typora PicGo-Core(command line) github  默认使用 githubPlus插件）

3.配置PicGo

```
cd /home/用户名/.config/Typora/picgo/linux
```

```
picgo set uploader
```


```
repo : 用户名/仓库名
brach : main/master
token :
path : image_Linux/
customUrl : https://cdn.jsdelivr.net/gh/用户名/仓库名
origin ：github
```

```
picgo use uploader
```

<br/>
配置完成配置文件模板

```
{
  "picBed": {
    "current": "github",
    "github": {
      "repo": "用户名/仓库名",
      "branch": "main",
      "token": "",
      "path": "image_Linux/",
      "customUrl": "https://cdn.jsdelivr.net/gh/用户名/仓库名"
    },
    "uploader": "github",
    "transformer": "path"
  },
  "picgoPlugins": {
    "picgo-plugin-github-plus": true
  }
}
```

<br/><br/><br/>

**For example**

![For example](https://github.com/north151/ImageBed1/blob/main/image_Linux/backiee-208791-landscape.jpg)



