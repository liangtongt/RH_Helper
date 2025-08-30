# 🔞 RH Helper

> 释放RH潜能的辅助工具，简单好用。
> 
>  helping tools to release RH potential. Simple and easy to use.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/liangtongt/RH_Helper)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

[下载地址](https://github.com/liangtongt/RH_Helper/releases)
[兼容的工作流](./wordflow_list.md)
[使用教程](https://www.youtube.com/watch?v=fux1POGj6YI)

## 🎉 更新
国内下载链接：https://pan.quark.cn/s/5ddf1e16242e 提取码：LT7Q

2025.08.30 v0.2.6
- 和T8辩论3天后最终屈服latent解码添加vae选择框，可自行下载vae模型到_internal\models\vae文件夹下,点击刷新列表即可选择vae模型。

2025.08.28 v0.2.5
- 添加快速去水印和质量去水印功能
- 添加去马赛克功能
- 修复了一些bug

2025.08.27 v0.2.2
- 添加图片超强去水印
- 修复了一些bug

2025.08.25 v0.2.1
- 发布cuda版本，比之前的cpu版本快，2G显存也能解码
- 模型下载管理


## ✨ Features
- ⚡️ 简单：开箱即用
- 🔧 零配置：双击即可运行
- 🌍 PC端支持：Windows
- 📱 移动端支持：android/ios(需PC启动服务)

## 🚀 functions 
- 图片latent解码
- 视频latent解码
- 图片去水印
- 支持的工作流推荐
- 👨‍🚀其他功能欢迎提建议~

## 📚 Describe
压缩包比较大是因为已经集成好所有环境依赖和模型，双击即可享用。

为了兼容性目前版本仅支持CPU环境，解码速度和CPU性能相关。i7 4核8线程2.8GHz CPU解码一张1M大的图片需要40秒左右。解码720P视频1s需要1分钟左右。

后续会支持GPU环境，提高解码速度。

在对比了常见VAE模型后，选择了vae-ft-mse-840000-ema-pruned.safetensors 作为默认模型，解码速度较快，占用内存少。需要兼容其他模型可自行下载放于comfyui/models/vae文件夹下。



## 🏁 Quick Start
```bash
1、解压到任意目录
2、双击run.bat运行
```

## 目录结构
```
├── internal      
├── comfyui.exe
├── ffprobe.exe         # web中预览视频必须
├── RH_Helper.exe
├── run.bat             # 👈双击启动   
├── run_cpu.bat         # cpu版本启动 
```

## 界面
PC端：

<img src="https://gitee.com/zhigan/rh_helper/raw/master/imgs/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250813173950.png" alt="PC" width="800"/>


移动端：

<img src="https://gitee.com/zhigan/rh_helper/raw/master/imgs/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20250813174057.jpg" alt="phone" width="300"/>


## comfyui大神版
有comfyui运行环境的大神可直接使用下述流程解码就行。

![workflow](https://gitee.com/zhigan/rh_helper/raw/master/imgs/decode_workflow.png)
1、下载图片直接拖入comfyui即可加载流程

2、需解码latent文件放入ComfyUI/input文件夹下

## 流程创作者兼容
仅需在最后一步保存图片或视频时添加蓝框部分即可
![workflow](https://gitee.com/zhigan/rh_helper/raw/master/imgs/encode_workflow.png)
可将兼容的流程链接通过issues提交，作者将会添加到兼容列表中。

## 免责说明
本软件仅供学习研究使用，请遵守当地相关法律法规，禁止用于任何商业用途，及非法用途，由此带来的法律责任与作者无关。
