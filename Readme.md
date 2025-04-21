# WHUT Beamer Theme

![License](https://img.shields.io/github/license/lxidea/WHUT-Beamer-Theme) ![Release](https://img.shields.io/github/v/release/lxidea/WHUT-Beamer-Theme)

武汉理工大学（Wuhan University of Technology）风格的Beamer演示文稿模板，专为学术报告、毕业答辩和技术分享设计。提供现代化的视觉风格和便捷的中文支持。

[➡ 立即查看模板樣例](https://github.com/lxidea/WHUT-Beamer-Theme/blob/main/blob/main/sample.pdf)  
[▼ 下载最新版本](https://github.com/lxidea/WHUT-Beamer-Theme/releases/latest)

## 主要特性

�� **主題風格**  
- 官方配色方案（理工藍、活力橙等）  
- 自適應深/淺主題元素  
- 現代化簡約設計風格  
- 全套預定義色彩主題（color theme）

�� **预设模块**
- 自适应封面页（自动填充作者/学院/日期）
- 多种版式可选的目录页
- 预定义区块样式（Alert Block/Example Block）
- 优雅的页脚进度指示
- 智能章节过渡页

�� **技术特性**
- 全面支持XeLaTeX/LuaLaTeX编译
- 内置常用数学符号包（amsmath, amssymb）
- 矢量图标支持（FontAwesome 5）
- 多图表布局预设（subfigure/multicol支持）
- PDF书签自动生成

�� **语言支持**
- 完整中文字体配置（无需额外设置）
- 自动处理中文标点挤压
- 双语标题支持（中英文自动切换）
- 智能引用格式（适应中文文献）

## 快速开始

### 基本使用

1. 克隆仓库或下载模板文件：
```bash
git clone https://github.com/lxidea/WHUT-Beamer-Theme.git

2. 在文档中引入主题：
\documentclass{beamer}
\usetheme{WHUT}

3. 设置文档信息：
\title{武汉理工大学演示模板}
\subtitle{Beamer Theme for WHUT}
\author{作者姓名}
\institute{学院名称}
\date{\today}

4. 开始构建内容：
\begin{document}

\frame{\titlepage}

\section{第一节}
\begin{frame}{框架标题}
  \begin{block}{标准区块}
    使用预定义的block环境
  \end{block}
  
  \begin{alertblock}{强调区块}
    重要内容提示
  \end{alertblock}
  
  \begin{itemize}
    \item 标准列表项
    \item 多级列表支持
  \end{itemize}
\end{document}

高级功能
添加数学公式
\begin{frame}{数学示例}
  傅里叶变换公式：
  \begin{equation}
    \hat{f}(\xi) = \int_{-\infty}^\infty f(x)\ e^{-2\pi i x \xi}\,dx
  \end{equation}
\end{frame}

插入图片
\begin{frame}{图形示例}
  \begin{figure}
    \includegraphics[width=0.8\textwidth]{demo-image}
    \caption{图片标题}
  \end{figure}
\end{frame}

模板预览
封面页
内容页
数学公式

贡献指南
欢迎通过以下方式参与改进：
1. 提交Pull Request修复问题
2. 在Issues区报告问题
3. 推荐给同学/同事使用
4. 完善文档和示例

许可证
本项目采用 MIT License，与武汉理工大学视觉标识的所有权归武汉理工大学所有。

© 2025 WHUT Beamer Theme 开发者 | lxidea

温馨提示：本模板为开源社区项目，与武汉理工大学官方无直接关联。