# SCRAPBRO 3分钟到12段15秒 LibTV 中文工作流

这是 SCRAPBRO WORLD 的中文 LibTV 视频生成工作流备份仓库。

## 文件

- `SCRAPBRO_3分钟到12段LibTV视频授权式工作流.md`：正式三分钟工作流原文。

## 用途

当你在另一台电脑上使用 Codex、LibTV 或其他工具时，可以下载本仓库，把工作流文件作为启动规则或参考文件使用。

核心逻辑：

1. 先稳定完整 3 分钟剧本。
2. 拆成 12 段，每段 15 秒。
3. 每段判断人物、场景、怪物、道具、FX 和分镜参考图需求。
4. 先生成完整 15 秒提示词，再生成分镜参考图。
5. 最后进入 LibTV 生成视频，并检查每段连续性。

## 下载方式

打开仓库页面，点击绿色 `Code` 按钮，然后选择 `Download ZIP`。

仓库地址：

https://github.com/richenyu/scrapbro-3min-libtv-workflow
