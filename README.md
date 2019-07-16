# rust-ffmpeg-sys

为了支持 ffmpeg 4.1+，fork 后作出如下修改

## 环境

1. 安装 ffmpeg (以 MacOS 为例)

```
brew install ffmpeg
```

2. 设置环境变量

```
export FFMPEG_DIR=/usr/local/Cellar/ffmpeg/4.1.4/
```

## Changelog

根据编译警告，修改 int64_t 为 i64