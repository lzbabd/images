# images
图床
picgo 插件
```
picgo add compress

picgo use transformer

picgo config plugin compress

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
      "token": "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",
      "path": "",
      "customUrl": "https://cdn.jsdelivr.net/gh/lzbabd/images@master",
      "origin": "github"
    },
    "transformer": "compress"
  },
  "picgoPlugins": {
    "picgo-plugin-github-plus": true,
    "picgo-plugin-rename-file": true,
    "picgo-plugin-compress": true
  },
  "picgo-plugin-github-plus": {
    "lastSync": "2021-09-16 02:34:26"
  },
  "picgo-plugin-rename-file": {
    "format": "{y}/{m}/{d}/{origin}-{hash}-{rand:6}"
  },
  "picgo-plugin-compress": {
    "compress": "tinypng",
    "key": "dK93hWvFshh2gBYF4MJJjXC7529mgS80",
    "nameType": "none"
  }
}

```
