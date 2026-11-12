# 参考驱动角色建模

一个用于 AI 角色建模的中文 Skill，针对实际建模中反复出现的失败模式整理：第一轮堆出完整模型后不断修补、衣服头发遮住形体问题、只看少数角度、缺少主动补参考，以及用局部轮廓对齐代替立体检查。

核心流程：**先定整体姿势和比例，再逐件细化；隐藏遮挡单独看，显示相邻部件看连接，恢复整体看协调。** 遇到结构不清楚的地方，主动寻找资料或生成造型参考。

适用于依据插画、设定图和照片制作或精修静态角色、手办与雕像。

## 安装

将仓库克隆到 Codex 的技能目录：

```sh
git clone https://github.com/whycantiusemyname/reference-character-modeling.git ~/.codex/skills/reference-character-modeling
```

## 使用

提供参考图片或现有模型，并调用：

```text
使用 $reference-character-modeling，参考这些图片建模，逐个部件检查和精修。
```

完整说明见 [SKILL.md](SKILL.md)。
