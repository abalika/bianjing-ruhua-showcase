# 来源与制作说明

## 原画参考

张择端《清明上河图》北京故宫博物院藏本。作品背景与史实参考[故宫藏品介绍](https://www.dpm.org.cn/collection/paint/228226.html)。原画参考取自[Wikimedia Commons原文件](https://commons.wikimedia.org/wiki/File:Alongtheriver_QingMing.jpg)，来源页面标记为Public Domain / PD-Art。公开展示的原画部分保持来源标注，不对原画主张新的独占权。

## 艺术化全景与声音

全景画面以原画风格及场景主题为灵感，使用AI辅助制作，并经过程序显示、相对深度处理和界面编排；它们不是原画像素的直接延伸，也不证明历史细节真实存在。

原项目制作涉及[Depth Anything V2 Small](https://github.com/DepthAnything/Depth-Anything-V2)（Small权重Apache-2.0）、[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)（BSD-3-Clause）及[Real-ESRGAN ncnn-vulkan](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan)（MIT）；网页使用[Three.js](https://github.com/mrdoob/three.js)（MIT）。本展示仓库不包含这些工具的程序、模型或运行包。

当前1.28.1视频中文旁白使用Microsoft云健（zh-CN-YunjianNeural），八景统一采用作品当前B音色设置，由[edge-tts](https://github.com/rany2/edge-tts)预生成后在网页本地播放；没有克隆指定真人，也没有使用参考影片的原音轨。旧1.28历史视频为[Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS)预设音色。展示视频包含程序实际播放的旁白音轨，不分发模型权重。

原项目古琴配乐为Charlie Huang演奏的《平沙落雁》（2006-04-23），[来源](https://commons.wikimedia.org/wiki/File:Pingsha_Luoyan.ogg)，采用[CC BY 2.5](https://creativecommons.org/licenses/by/2.5/)。展示视频包含该录音节选，保留程序中的音量渐变与解说让位效果，转码为AAC；没有提供独立音频下载。音乐是现代录音，不是宋代声音复原。

## 截图

本仓库images目录为原项目1.28版本的实际运行截图，保留完整程序画面，没有附带代码、深度数据、全景母图或可运行程序。
