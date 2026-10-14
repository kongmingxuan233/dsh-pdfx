# dsh-pdfx
DeepSeek Harness 的PDF 解析插件。它把工作区会话里准备好的 `pdfx` 解析库包装成四个 Agent 工具， 让ai可以直接读取 PDF 的结构、文字层和页面图片，不需要 poppler / mutool / Ghostscript 之类的 外部程序，也不需要联网或额外安装 Python 包（只用 Pillow 处理像素）。  - 插件类型：Host-only bundle（没有客户端半边，不需要 index 注入） - 工具数量：4 - 运行时依赖：一个能 `import PIL` 的 Python 解释器（自动探测，默认用 DSH 自带的那一个)
