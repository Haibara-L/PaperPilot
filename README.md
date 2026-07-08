#  PaperPilot (AI科研导师)

> 专为科研新手打造的论文深度研读与全栈智能化工作台。

PaperPilot 旨在解决本科生和低年级研究生在精读顶级英文期刊时的痛点——**语言断层、背景知识缺失、论文宏观逻辑迷失、实验步骤抽象**。传统工具大都局限于死板的“单文档单向问答”，而 PaperPilot 通过全栈 AI 联动，将静态的 PDF 转化为一个高交互性的沉浸式学术空间。

## 核心亮点

* **“左右护法”学术工作台布局**：打破传统通栏，论文居中，AI 助手左侧伺候，高阶工具链右侧常驻。
* **双模智适应系统**：内置离线演示模式（以经典论文《Attention Is All You Need》为例）与在线真全栈模式。完美兼容无后端环境的快照预览。
* **向心力交互知识图谱**：基于 SVG/Canvas 动态解析论文的核心概念网络，支持沉浸式全屏放大与节点“中心聚焦”动态交互。
* **动态中英对照与引文动机溯源**：支持平滑滑出的段落级翻译；点击正文引用上标即可原地弹出毛玻璃引文详情浮窗。
* **读图专区与实验看板**：一键提取论文插图（如 Transformer 架构图）进行 AI 识图，并将枯燥的 Experiment 文本转化为可勾选的实验还原流水线。

## 🛠️ 技术栈

* **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript (原生高阶交互)
* **Backend**: Python, FastAPI, PyPDF2
* **AI Engine**: 大模型 API 结构化 JSON 输出 (Structured Outputs)
* **Powered By**: TRAE Work (Auto Mode)
