# qiniu-image-tool-mac
**qiniu-image-tool-mac** 是一个 macOS 中提升 Markdown 贴图体验的实用小工具，基于 Alfred 实现，可以自定义快捷键或关键字，一键上传图片或截图至七牛云，获取图片的原始 URL 或 Markdown 引用至剪贴板，并自动粘贴到当前编辑器，使用简单方便。

# Usage
详细的使用教程请参考：[使用alfred在markdown中愉快的贴图](http://jverson.com/2017/04/28/alfred-qiniu-upload/)     
windows版本请移步至：https://github.com/jiwenxing/qiniu-image-tool-win


## Features
- 支持 jpg、png、bmp 及 gif 等各种图片格式
- 支持截图及网络图片直接复制上传
- 支持各种其它格式本地文件上传，返回资源引用
- 上传失败或成功通知栏会有相应提示
- 使用简单，只需配置环境变量即可
- **可根据需要选择返回资源原始 URL 或 Markdown 引用** （\*新增\*）
- **支持自定义文件名前缀** （\*新增\*）

## Requirements
**`Alfred with Powerpack`** **`qshell`** **`七牛账号`**

## Preview
1. 本地图片文件上传 <br/>
![](https://raw.githubusercontent.com/jiwenxing/qiniu-image-tool/master/res/local.gif)

2. 截图上传  <br/>
![](https://github.com/jiwenxing/qiniu-image-tool/blob/master/res/paste.gif?raw=true)

3. 其它文件上传  <br/>
![](https://raw.githubusercontent.com/jiwenxing/qiniu-image-tool/master/res/file.gif)


> 演示 gif 使用 macdown 及 licecap 制作


# License
MIT License.     
Copyright (c) 2017 Tank

**本项目基于 Jverson 的项目 https://github.com/jiwenxing/qiniu-image-tool 稍作修改。**