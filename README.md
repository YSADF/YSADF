

AI 应用开发，关注文档处理、OCR 与 Agent / RAG。我负责把识别、检索和模型能力接入可运行的业务流程，并保留输入、配置、结果与失败记录，让工程结论能够核查。

**Python · FastAPI · PaddleOCR · OpenCV · PyMuPDF · LangGraph · SQLite · Docker**

## 项目展示

| 项目 | 解决的问题 | 公开证据 |
|---|---|---|
| [OCR 与文档结构化](https://github.com/YSADF/ocr-document-showcase) | PDF / 扫描页解析、工程字符保护、合并表格与版式交付 | RTX 5090：20 张真实图纸、238 个选定区域、40 次对照推理；工程模式机械转写 74/118、P&ID 113/120；17 个直径符号仍失败，全部页面待复核；公开方法与精简评分代码 |
| [文档 Agent 与 RAG](https://github.com/YSADF/agent-rag-showcase) | 带引用的问答、跨文档核对、审批与调用去重 | 18 份虚构文档、24 道题，真实本地 Qwen 模型；JSON 约束补齐后任务完成 19/24 → 24/24；仍记录来源归属问题 |

两个仓库只公开精选可运行片段、公开样本、评测客户端和实测产物。模型与框架来自开源项目；我的贡献集中在文档链路、业务编排、状态管理、异常处理与部署验证。

数字都附有测量范围与证据说明。真实图纸标注由助手目视核对，尚待独立人工复核；选定区域转写和小规模合成测试都不等于生产准确率，待复核不计为验收正确，字段检查通过也不等于逐句语义完全正确。

[OCR 真实图纸实测](https://github.com/YSADF/ocr-document-showcase/blob/main/cases/real-engineering-drawings.md) · [Agent 实测方法](https://github.com/YSADF/agent-rag-showcase/blob/main/EVALUATION.md)
