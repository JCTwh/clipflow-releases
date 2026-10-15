# 切片工场 · Windows 下载与更新

这里仅发布 Windows x64 安装包及自动更新文件，不包含私有源码仓库、用户素材、字幕数据库或模型密钥。

[下载最新安装包](https://github.com/JCTwh/clipflow-releases/releases/latest)

首次安装支持自动更新的版本后，应用启动检查、后台下载；更新完成后点击“保存并重启升级”。不会在转写、导入或导出期间强行重启。本机项目、字幕缓存与模型配置保留。

旧的 0.1–0.7 安装版没有自动更新模块，需要最后手动安装一次 0.8 或更新版本。

每个版本包含安装包、blockmap、latest.yml、release-info.json、SHA256SUMS.txt。请核对文件摘要，并只从本仓库下载。

当前尚未配置商业代码签名证书，Windows 可能提示未知发布者。Electron 桌面 JavaScript 可从安装包解包，源码仓库私有不等于二进制不可逆向。

自动更新不包含 Python/Whisper 运行环境或额外模型下载，也不上传本机的视频素材或模型配置。
