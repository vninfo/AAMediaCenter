# AAMediaCenter
一个可以在线播放mp3和flac格式的播放器（含下载功能） 本播放器参考OrigamiEngine的核心代码，并将原OrigamiEngine的MRC环境改成ARC环境，缓存部分由原来的NSURLConnection更新为使用NSURLSession，并增加下载管理器功能。 本播放器将歌曲在线缓存播放与歌曲下载管理融为一体，缓存播放的歌曲可一键转换为下载歌曲，减少重复下载造成的流量损耗。
