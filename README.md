# 西瓜-IP型产品设计

把知识IP、专业服务者或一人公司的用户证据、服务卡点、真实案例和独特方法，转化为有具体场景、用户参与、可信故事转折、可传播结果和高价值服务承接的产品。

这里的 IP 指知识IP与专业服务IP，不是影视、动漫或潮玩角色IP。

## 它解决什么

很多IP产品最后只剩两种形态：

- 把内容装进课程、知识库或小程序；
- 做一个有用但通用、没有IP判断和传播故事的工具。

本 Skill 将“机会发现、故事化体验、轻量PRD和实验迭代”连成一条工作流：

```text
读取真实素材
→ 区分证据与假设
→ 发现产品化机会
→ 生成产品故事简报
→ 验证可信转折与传播对象
→ 生成轻量PRD
→ 收集实验反馈
→ 产生下一版本
```

## 核心能力

### 1. 从证据找产品机会

从用户的高价值时刻、服务中的重复卡点、IP已有方法和可承接服务的交叉点中，寻找最多3个产品方向。

### 2. 把产品设计成故事生成器

产品不是替用户编故事，而是让用户通过自己的选择和输入，获得一个有依据的认知转折：

```text
具体时刻
→ 低压力选择
→ 提供个人证据
→ 形成判断悬念
→ 出现可信转折
→ 获得可控行动
```

### 3. 生成轻量PRD和反馈工作台

需求明确时生成产品故事简报、轻量PRD和实验记录；需要用户补充或选择时，可生成本地运行的产品定义工作台。

### 4. 用实验判断下一版

实验失败时不默认增加功能，而是区分入口、完成、价值、传播和商业承接分别出了什么问题，再决定修改体验、修改最小结果或停止方向。

## 传播力标准

每个产品进入PRD前检查：

- 场景是否具体；
- 用户是否真正参与；
- 结果是否与用户本人有关；
- 是否产生可信的认知转折；
- 结论是否有依据；
- 用户能否用一句第一人称表达复述；
- 分享时是否保护身份与隐私；
- 判断是否体现IP独特方法。

传播力不等于分享按钮，也不承诺必然爆款。不使用恐惧、羞辱、虚假排名、隐私暴露或夸大结果制造传播。

## 文件结构

```text
ip-product-design/
├── SKILL.md
├── README.md
├── LICENSE
├── agents/
│   └── openai.yaml
├── references/
│   └── story-engine.md
└── templates/
    ├── product-story-brief.md
    ├── lightweight-prd.md
    ├── experiment-log.md
    └── product-feedback-studio.html
```

## 默认产物

```text
product-experiments/<product-slug>/
├── story-brief-v0.1.md
├── feedback-studio-v0.1.html
├── PRD-v0.1.md
└── experiment-log.md
```

## 安装

### Codex

```bash
git clone https://github.com/hiiiwatermelon/ip-product-design.git
cp -r ip-product-design ~/.codex/skills/
```

调用：

```text
$ip-product-design
```

界面显示名为“西瓜-IP型产品设计”。保留 `ip-product-design` 作为仓库和调用标识，避免旧链接与已有调用失效。

### WorkBuddy

```bash
cp -r ip-product-design ~/.workbuddy/skills/
```

安装或更新后，通常需要重启对应客户端。

## License

MIT
