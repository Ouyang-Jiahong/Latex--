# LaTeX 项目说明文档

本项目为一个结构化的 LaTeX 写作模板，适用于书籍、论文或长文档的编写。以下是各文件的功能说明与使用方式。

## 文件结构说明

- **`book.tex`**  
  主文档文件。正文内容（包括章节、段落等）应在此文件中编写。

- **`title.tex`**  
  封面配置文件。用于设置封面格式及输入封面相关文字信息（如书名、作者、日期等）。

- **`package.tex`**  
  宏包与自定义命令配置文件。所有需要引入的 LaTeX 宏包以及用户自定义命令建议在此文件中统一管理。

- **`latex-workshop/` 目录**  
  包含适用于 [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) 插件的配置文件。  
  使用方法：
  1. 打开 VS Code；
  2. 替换 `.vscode/package.json` 文件为该目录下的 `package.json`；
  3. 在 VS Code 中按下快捷键 `Ctrl + Alt + B` 编译项目。

## 使用建议

- 所有主要编辑工作应在 `book.tex` 中完成；
- 若需修改文档样式或引入新的宏包，请编辑 `package.tex`；
- 封面内容和格式可在 `title.tex` 中调整；
- 推荐使用 VS Code 配合 LaTeX Workshop 插件进行编译与预览。

## 编译方式

在配置好 LaTeX 环境与插件后，使用 `Ctrl + Alt + B` 快捷键即可一键编译生成 PDF 文档。