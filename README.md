# fetch-audio-from-fm
Forked from zhenze12345/fetch-audio-from-fm<br/>
从FM网站批量下载专辑的音频，并可选择转换到MP3格式<br/>

## 支持网站
- [喜马拉雅](https://www.ximalaya.com)
- [蜻蜓FM](https://www.qingting.fm)
- [荔枝FM](https://www.lizhi.fm)

## 使用方法
ruby [script] [url] [filter] --[extra_args]

以ximalaya为例，如果希望下载标题包含某个词(如:汾河湾)的音频，可以使用<br/>
ruby ximalaya https://www.ximalaya.com/xiangsheng/9723091 汾河湾<br/>
如果希望转换为mp3<br/>
ruby ximalaya https://www.ximalaya.com/xiangsheng/9723091 汾河湾 --convert_to_mp3<br/>

## 注意
如需转换，除lizhi以外，其他网站必须安装ffmpeg

## 依赖
- https://github.com/YorickPeterse/oga
- https://github.com/rdp/os
- https://www.ffmpeg.org

## Notes
- ximalaya是[https://github.com/zhenze12345/ximalaya](https://github.com/zhenze12345/ximalaya)的多线程版本
