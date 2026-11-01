# 大象Poker — 中文牌桌的 GTO 工作台

**GTO 不该是英文作业，它应该是下一手就能用的建议。**

单文件 HTML，打开即用。无需安装，无需注册。面向国内 MTT / 俱乐部周常 / 鱿鱼桌。

[**直接打开使用**](https://raw.githubusercontent.com/HaowenY0/personal-grok-skills/main/elephant-poker/%E5%A4%A7%E8%B1%A1Poker.html)

---

## 为谁做的

- 一线 / 新一线俱乐部会员
- 城市 MTT 常客
- 现金鱿鱼桌常客

不跟 Pio 比树的深度，只把「当前这手」说清楚。

## 三个核心功能

### 1. 跟进本手
手牌、对家动作、建议在同一屏。
底牌锁定，翻前 → 翻牌 3 张 → 转牌 → 河牌按规则走。
加注档位直接比 EV。

### 2. 对手范围穷举
不用自己先画 169 格。
系统按权重列出对手还可能有什么牌，矩阵同步上色。

### 3. 鱿鱼专业测算
无鱿人数、边池 EV、抢主池 ΔEV、感知前注。
国内现金桌高频变体，国际 Solver 几乎不碰的地方。

## 怎么用

1. 点击上方链接，或下载 `elephant-poker/大象Poker.html`
2. 用 Chrome / Edge 打开
3. 点「游客进入」
4. 选 MTT 或鱿鱼，进入跟进模式

全部本地运行，不依赖后端。

## 仓库结构

```
elephant-poker/
├── 大象Poker.html      # 完整单文件解算器
├── SKILL.md
├── CHANGELOG.md
└── evals/
```

## 其他 Skills

同仓库还包含：
- `resume-builder` — 简历生成
- `official-document` — 正式中文文档
- `elephant-gto` — GTO 策略模板

---

适合每周都要坐下来的人。

如有问题或建议，欢迎开 Issue。
