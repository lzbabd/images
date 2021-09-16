# images
图床
picgo 插件
```
picgo install github-plus

picgo install rename-file

```

picgo 配置

```
{
  "picBed": {
    "uploader": "githubPlus",
    "current": "githubPlus",
    "githubPlus": {
      "repo": "lzbabd/images",
      "branch": "master",
      "token": "xxx",
      "path": "",
      "customUrl": "https://cdn.jsdelivr.net/gh/lzbabd/images@master",
      "origin": "github"
    }
  },
  "picgoPlugins": {
    "picgo-plugin-github-plus": true,
    "picgo-plugin-rename-file": true
  },
  "picgo-plugin-github-plus": {
    "lastSync": "2021-09-16 11:41:59"
  },
  "picgo-plugin-rename-file": {
    "format": "{y}/{m}/{d}/{hash}-{origin}-{rand:6}"
  }
}

```
