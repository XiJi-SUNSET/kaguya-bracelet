# Kaguya's Bracelet · 辉夜姬的手镯

把动画里那只手镯做出来：**TC4 钛合金 3D 打印 → 手工打磨 → 在家阳极氧化上色**。

这份仓库只放两样东西——**一份单文件说明书**，和**模型文件的发行版下载**。

## 在线阅读

GitHub Pages（启用后填这里）：`https://<你的用户名>.github.io/kaguya-bracelet/`

也可以直接下载 `index.html` 双击打开：图片、字体、样式全部内嵌，不依赖网络，也不需要同目录任何素材。

## 下载模型

四个版本分开打包，进 [Releases](../../releases) 选需要的那个：

| 安装包 | 版本 | 内径 | 带宽 | 说明 |
| --- | --- | --- | --- | --- |
| [`bangle-movie-66.zip`](../../releases/latest/download/bangle-movie-66.zip) | 剧场版 | 66 mm | 7 mm | 作者自用尺寸（6 MB） |
| [`bangle-artbook-66.zip`](../../releases/latest/download/bangle-artbook-66.zip) | 设定集版 | 66 mm | 5 mm | 更窄更轻，线条更收（8 MB） |
| [`bangle-movie-74.zip`](../../releases/latest/download/bangle-movie-74.zip) | 剧场版 | 74 mm | 7 mm | 手更大的人，开口 5.5 mm（10 MB） |
| [`bangle-artbook-74.zip`](../../releases/latest/download/bangle-artbook-74.zip) | 设定集版 | 74 mm | 5 mm | 开口收窄到 3.5 mm，穿脱余量更小（13 MB） |

每个包内含 `打印文件.stl`、`源文件.blend` 与 `规格.txt`。校验值见 [`SHA256SUMS.txt`](../../releases/latest/download/SHA256SUMS.txt)。

模型不随仓库分发（`*.stl` / `*.blend` 已在 `.gitignore` 里），原因很简单：仓库要能一秒 clone，实体文件走 Releases 更合适。

## 说明书里有什么

1. **确定尺寸** —— 两组实测比例，怎么从动画比例换算到能戴进去的尺寸
2. **3D 打印** —— TC4 / SLM 的材料与工艺，下单要问清的几件事，收到件怎么验
3. **打磨** —— 100 → 120 → 240 目，从层纹到缎面
4. **阳极氧化** —— 4 节 9V 电池、小苏打、钛丝，约 36V 出冰蓝
5. **常见问题** —— 评论区里问得最多的那些

## 部署（维护者）

仓库根目录的 `index.html` 就是整份说明书。在 **Settings → Pages** 里选 `Deploy from a branch` → `main` / `root` 即可。

> 注意：私有仓库要用 Pages 需要 GitHub Pro；免费账号下 Pages 只对公开仓库开放。

## 作者

**大肥鱼** · **渺**

全文已经人工订正过，但受限于水平，经验肯定比不上工业级或实践次数更多的爱好者。**欢迎提 Issue 或 PR 订正。**

## 授权

- 说明书文字与自制插图：CC BY-NC 4.0（署名 · 非商业）
- 模型文件（STL / BLEND）：仅限个人非商业使用，转载与二次分发请注明出处
- 动画截图与设定集素材版权归原作者及版权方所有，仅作个人学习对照，未随仓库分发
