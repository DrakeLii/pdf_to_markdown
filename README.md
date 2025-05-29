# Pdf To Markdown

将英文 PDF 文件转换为中文 Markdown 格式的流程

## 拆分 PDF （如有需要）

使用 [ilovepdf](https://www.ilovepdf.com/zh-cn/split_pdf#split,range "跳转到 ilovepdf") 拆分 PDF 文件

## PDF To Markdown

使用 [marker](https://github.com/VikParuchuri/marker "跳转到 marker") 将 PDF 文件转换为 Markdown 文件

## 处理 Markdown 文件标题层级

使用 reset_markdown_headings.py 重置 Markdown 文件标题层级

## 处理  Markdown 文件表格格式（如有需要）

使用 convert_html_table_to_markdown_table.py 将 Markdown 内 Html 格式表格处理为 Markdown 标准表格格式
或使用 [html-to-markdown](https://tableconvert.com/html-to-markdown "跳转到 tableconvert") 在线转换工具将 Html 格式表格转换为 Markdown 标准表格格式。

## 翻译 Markdown 文件

使用 DeepSeek 翻译 Markdown 文件