# 🎬🤖 Welcome to the AI Image Toolbox! 🚀✨

[中文](README_zh.md) | [English](README.md) | [日本語](README_ja.md)

This is the open-source version of the [AI Image Toolbox](https://302.ai/tools/pictool/) from [302.AI](https://302.ai). You can directly log in to 302.AI to use the online version with zero code and zero background, or modify and deploy it yourself according to your requirements.

## ✨ Introduction to 302.AI ✨

[302.AI](https://302.ai) is a pay-as-you-go AI application platform that solves the last mile problem of AI for practical use.

1. 🧠 It aggregates the latest and most comprehensive AI capabilities and brands, including but not limited to language models, image models, sound models, and video models.
2. 🚀 Deep application development on basic models, we develop real AI products, not simple chatbots.
3. 💰 Zero monthly fee, all features are pay-as-you-go, fully open, achieving genuinely low barriers and high ceilings.
4. 🛠 Powerful management backend, aimed at teams and small to medium-sized enterprises, managed by one person, used by many.
5. 🔗 All AI capabilities provide API access, all tools can be self-customized (in progress).
6. 💡 A strong development team launching 2-3 new applications weekly, with daily product updates. Developers interested in joining are welcome to contact us.

## Project Features

1. 🎥 **AI Image Toolbox**: Supports various image operations, including extended functionality like text to image and image to video.
2. 🖼️ **Comprehensive Features**: Supports over ten functions such as image cropping/expanding/modifying/enlarging/coloring/face changing/filters.
3. 🔄 **Task Management**: Tasks support regeneration, chained tool calls, historical rollback for re-editing.
4. ⚙️ **Multi-Model Support**: Choose from various models to generate images and videos.
5. 📜 **History Records**: Save your creative history, memory never lost, downloadable anytime, anywhere.
6. 🌐 **Internationalization**: Supports multiple languages, currently Chinese, English, and Japanese.

## Technology Stack

- Next.js 14 basic framework
- Tailwind CSS + Shadcn UI style UI
- Zustand for data management

## Development & Deployment

1. Clone the project `git clone git@github.com:302ai/302_image_toolbox.git`
2. Install dependencies `pnpm install`
3. Configure the 302 API KEY by referring to .env.example
4. Run the project `pnpm dev`
5. Build and deploy `docker build -t image_toolbox . && docker run -p 3000:3000 image_toolbox`

## Interface Preview

![pic-tool](docs/zh/pic-tool.png)
