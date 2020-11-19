# x264-t_mod-posix

从 [x264-t_mod原项目](https://github.com/jpsdr/x264) 搬运得到，并用 JSdelivr 作为CDN加速，使用工具 [ReleaseDelivr](https://github.com/One-Studio/ReleaseDelivr)

## 最新下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/x264-t_mod-posix@master/dist/x264-t_mod-posix.7z

## 某个版本的下载链接

通过下面的API接口获取历史版本号，比如 `r2333`，下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/x264-t_mod-posix@r2333/dist/x264-t_mod-posix.7z

## 本搬运仓库API：

版本号：https://cdn.jsdelivr.net/gh/One-Studio/x264-t_mod-posix@master/version

下载链接（ `/n` 分割）：https://cdn.jsdelivr.net/gh/One-Studio/x264-t_mod-posix@master/download_link

API接口 Json格式：https://cdn.jsdelivr.net/gh/One-Studio/x264-t_mod-posix@master/api.json

| API          | 类型     | 含义                                          |
| ------------ | -------- | --------------------------------------------- |
| Version      | string   | 版本号                                        |
| VersionList  | []string | 历史版本                                      |
| ReleaseTime  | string   | 最新版本的发布时间 (格式2020-10-20T12:16:01Z) |
| Checktime    | string   | 搬运时检查的时间                              |
| DownloadLink | []string | 下载链接                                      |
| Format       | int      | 格式(1=7z, 2=zip)                             |
| ReleaseNote  | string   | 更新日志                                      |