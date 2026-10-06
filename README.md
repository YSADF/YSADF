# YSADF

你好，我是 YSADF。我在公司独立负责 OCR 文档系统的设计、开发与部署。

我的工作覆盖 PDF/图片解析、文字识别、版面与表格处理、结构化输出，以及相关组件集成和服务部署。我关注文字、位置与文档结构之间的对应关系，让识别结果能够用于编辑、检索和后续业务处理。

**技术栈：** Python · PaddleOCR · OpenCV · PyMuPDF · Docker · ONNX Runtime

## 项目展示

### [OCR 与文档结构化系统](https://github.com/YSADF/ocr-document-showcase)

通过公开样本、处理结果和独立演示脚本，展示我的 OCR 文档处理经验，包括 PDF 解析、页面坐标转换、合并单元格结构表达及结果核查。

- [工程 PDF 文字与坐标案例](https://github.com/YSADF/ocr-document-showcase/blob/main/cases/engineering-pdf.md)：使用 DEXPI C03 公开工程图，展示 PDF 原生文字提取、文字位置框和坐标 JSON。
- [合并单元格表格案例](https://github.com/YSADF/ocr-document-showcase/blob/main/cases/merged-table.md)：使用自制公开样本，展示跨行、跨列合并和人工定义的结构真值。

当前案例展示原生文字解析基线与表格结构真值。模型 OCR、表格结构预测及可编辑 Word 输出效果仍待实测，结果状态与复现方法见项目文档。

## 联系

欢迎通过 [GitHub](https://github.com/YSADF) 查看项目与交流。
