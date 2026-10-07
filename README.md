

AI 应用开发，关注文档处理、OCR 与 Agent / RAG。我负责把识别、检索和模型能力接入可运行的业务流程，并保留输入、配置、结果与失败记录，让工程结论能够核查。

**Python · FastAPI · PaddleOCR · OpenCV · PyMuPDF · LangGraph · SQLite · Docker**

## 项目展示

| 项目 | 解决的问题 | 公开证据 |
|---|---|---|
| [OCR 与文档结构化](https://github.com/YSADF/ocr-document-showcase) | PDF / 扫描页解析、工程字符保护、合并表格与版式交付 | RTX 5090 两个公开案例，各 20 次请求；表格文字 19/21 格完全匹配、5/5 合并关系匹配；同时公开 Word 渲染缺陷 |
| [文档 Agent 与 RAG](https://github.com/YSADF/agent-rag-showcase) | 带引用的问答、跨文档核对、审批与调用去重 | 18 份虚构文档、24 道题，真实本地 Qwen 模型；JSON 约束补齐后任务完成 19/24 → 24/24；仍记录来源归属问题 |

两个仓库只公开精选可运行片段、公开样本、评测客户端和实测产物。模型与框架来自开源项目；我的贡献集中在文档链路、业务编排、状态管理、异常处理与部署验证。

数字都附有测量范围与原始记录。小规模合成测试不等于生产准确率，字段检查通过也不等于逐句语义完全正确。

[OCR 实测方法](https://github.com/YSADF/ocr-document-showcase/blob/main/EVALUATION.md) · [Agent 实测方法](https://github.com/YSADF/agent-rag-showcase/blob/main/EVALUATION.md)
