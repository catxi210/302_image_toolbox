# <p align="center">🖼️ AI 图片工具箱 🚀✨</p>

<p align="center">AI图片工具箱提供了各种丰富的AI处理图片功能，还可以连续进行链式操作。</p>

<p align="center"><a href="https://302.ai/tools/word/" target="blank"><img src="https://file.302ai.cn/gpt/imgs/badge/21212.png" /></a></p >

<p align="center"><a href="README zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>


这是来自[302.AI](https://302.ai)的[AI图片工具箱](https://302.ai/tools/pictool/)开源版本。你可以直接登录302.AI，零代码零基础使用在线版本，或根据自己的需求修改并自行部署。

## 界面预览
![pic-tool](docs/zh/pic-tool.png)
![pic-tool](docs/zh/图片工具箱1.png)

## 项目特性
### 🎥 AI图片工具箱
  支持多种图片操作，包括拓展功能文字生图跟图片转视频。
### 🖼️ 功能一应俱全
  包括去除背景、物体消除、背景替换、图片矢量化、图片放大、超级图片放大、黑白图片上色、AI换脸、图片扩展、图片修改、以图生图、草稿生图、图片裁剪、图片调色、图片拼接、人物滤镜等功能。
### 🔄 任务管理
  任务支持重新生成，链式调用各种工具，历史回滚再次编辑。
### ⚙️ 多模型支持
  可选择各种模型生成图片跟视频。
### 📜 历史记录
  保存您的创作历史,记忆不丢失，随时随地都可以下载。
### 🌍 多语言支持
  - 中文界面
  - English Interface
  - 日本語インターフェース

## 技术栈

- Next.js 14 基础框架
- Tailwind CSS + Shadcn UI 样式UI
- Zustand 作为数据管理

## 开发&部署

1. 克隆项目 `git clone git@github.com:302ai/302_image_toolbox.git`
2. 安装依赖 `pnpm install`
3. 配置302的API KEY 参考.env.example
4. 运行项目 `pnpm dev`
5. 打包部署 `docker build -t image-toolbox . && docker run -p 3000:3000 image-toolbox`


## ✨ 302.AI介绍 ✨

[302.AI](https://302.ai)是一个按需付费的AI应用平台，为用户解决AI用于实践的最后一公里问题。

1. 🧠 集合了最新最全的AI能力和品牌，包括但不限于语言模型、图像模型、声音模型、视频模型。
2. 🚀 在基础模型上进行深度应用开发，我们开发真正的AI产品，而不是简单的对话机器人。
3. 💰 零月费，所有功能按需付费，全面开放，做到真正的门槛低，上限高。
4. 🛠 功能强大的管理后台，面向团队和中小企业，一人管理，多人使用。
5. 🔗 所有AI能力均提供API接入，所有工具开源可自行定制（进行中）。
6. 💡 强大的开发团队，每周推出2-3个新应用，产品每日更新。有兴趣加入的开发者也欢迎联系我们。
