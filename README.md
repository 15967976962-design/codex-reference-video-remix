# 参考短视频语义精剪 Skill

这是一套用于抖音商品短视频的参考分析、素材检索、语义匹配、精剪和成片质检流程。

它不包含任何人的原始素材、参考视频、商品资料、账号信息或历史成片。安装者使用自己的参考视频和素材库。

## 安装

把本仓库中 `reference-video-remix` 文件夹的 GitHub 链接复制给 Codex，并发送：

```text
请使用 skill-installer 安装这个 Skill：<reference-video-remix 文件夹链接>
```

公开仓库无需协作者邀请。安装完成后，新建任务或在下一轮消息中明确调用：

```text
使用 $reference-video-remix 处理这条参考视频：<路径>。
产品是：<产品名>；原始素材库：<路径>。
保留参考视频原声，制作 5 条 9:16 待审核版本。
未经我确认，不要放入正式成品库。
```

## 包含内容

- `SKILL.md`：完整工作流程与关键判断规则
- `references/宽版发圈案例.md`：经过多轮实践修正的语义与镜头案例
- `references/work-templates.md`：分句、候选镜头、EDL、多版本差异和质检表
- `references/quality-gate.md`：交付前成片检查
- `references/team-setup.md`：跨电脑安装与团队使用

## 运行条件

Skill 负责方法和判断。执行电脑还需具备可用的视频读取、抽帧、转码和检查能力，例如 FFmpeg。首次使用时可让 Codex 先检查运行环境。


