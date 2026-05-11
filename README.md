<p align="center">
  <h1 align="center">不读论文 · Skill</h1>
</p>

<p align="center">
  不是真的不读论文，是真的不想痛苦地读论文。
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">
  <img alt="ChatGPT Skill" src="https://img.shields.io/badge/ChatGPT-Skill-10a37f">
  <img alt="LaTeX" src="https://img.shields.io/badge/output-LaTeX-orange">
  <img alt="PDF" src="https://img.shields.io/badge/input-PDF-red">
  <img alt="Bilingual" src="https://img.shields.io/badge/language-中文%20%7C%20English-purple">
</p>

<p align="center">
  <strong>把 PDF 论文丢进去，把能用的东西捞出来。</strong>
</p>

---

## 这是什么？

**不读论文 · Skill** 是一个用于学术论文精读的 ChatGPT Skill。

它不是让你逃避论文，而是帮你把论文从一团高密度学术压缩包，拆成一份结构化、可修改、可复盘的中英双语 LaTeX 精读笔记。

它不满足于生成几句摘要，而是会继续追问：

- 这篇论文到底想解决什么问题？
- 它真正的新东西在哪里？
- 它和已有模型、代表方法有什么区别？
- 方法流程和关键公式应该怎么理解？
- baseline 和代表模型到底是怎么工作的？
- 重要术语是什么意思？
- 实验结果说明了什么？
- 这篇论文能不能复现？
- 它放在当前国际研究现状里，算什么位置？

如果普通摘要是在论文门口拍照打卡，  
那 **不读论文** 更像是进去转了一圈，画了地图，标了坑位，还顺手写了一份 LaTeX 施工文档。

---

## 它能做什么？

把 PDF 丢进去，它会尽量输出：

- **核心摘要**：一句话总结、重点总结、详细理解
- **创新点分析**：不只列贡献，还解释为什么重要
- **方法讲解**：从整体流程到模块拆解
- **关键公式解释**：公式含义、符号说明、直觉理解
- **代表模型解析**：baseline、prior work、相关方法如何工作
- **模型对比**：本文方法和已有方法到底差在哪
- **术语解释**：重要概念的中英双语说明
- **实验结论**：结果说明了什么，不说明什么
- **可复现性分析**：代码、数据、超参、训练成本、复现难度
- **国际现状分析**：论文在当前研究版图中的位置

默认策略：

> 先基于 PDF。  
> PDF 不够时，再联网补充。  
> 补充内容会和论文原文信息明确区分。

---

## 适合谁？

适合这些场景：

- 你有一堆论文要快速筛选
- 你想把论文整理成长期可维护的笔记
- 你需要理解方法、公式和 baseline
- 你要写 literature review
- 你想复现一篇论文，但不想从零开始拆
- 你看完摘要还是觉得自己什么都没看懂

---

## 使用方式

下载 `skill.zip`，然后在 ChatGPT Skills 中上传使用。

如果你的 AI 平台不支持 Skill，也可以直接打开：

```text
SKILL.md
