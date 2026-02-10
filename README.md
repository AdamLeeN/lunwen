# 南昌大学硕士学位论文Overleaf模板使用说明

## 📁 文件结构

```
Overleaf模板/
├── main.tex          # 主文件（直接上传到Overleaf）
└── README.md         # 使用说明
```

## 🚀 如何使用

### 方法一：直接上传到Overleaf
1. 打开 [Overleaf官网](https://www.overleaf.com)
2. 创建新项目或打开现有项目
3. 将 `main.tex` 文件内容复制到Overleaf编辑器中
4. 编译查看效果

### 方法二：下载文件上传
1. 下载整个 `Overleaf模板` 文件夹
2. 将文件夹打包上传到Overleaf
3. 打开 `main.tex` 开始编辑

## 📝 如何填写论文信息

在 `\begin{document}` 之前，找到以下命令并修改：

```latex
% ============ 论文信息设置 ============
\classification{分类号}           % 如：TP391
\udc{UDC号}                       % 如：004.9
\studentid{学号}                  % 如：4101200001
\schoolname{南昌大学}
\thesistitle{你的论文题目}         % 中文题目
\thesistitleen{Your Title}        % 英文题目
\authorname{你的姓名}
\college{你的学院}                 % 如：信息工程学院
\supervisor{导师姓名}
\supervisorsecond{第二导师（可选）}
\major{你的专业}                   % 如：计算机技术
\dateinput{2026}                  % 年份
```

## ✏️ 常见修改

### 修改论文题目
直接修改 `\thesistitle{}` 和 `\thesistitleen{}` 中的内容。

### 修改作者信息
在论文信息设置部分修改各个字段。

### 修改页眉
默认页眉显示章节名称，如需修改请查看 `\pagestyle{fancy}` 部分。

### 添加新章节
使用 `\chapter{章节标题}` 添加新章节。

### 添加参考文献
在 `\begin{thebibliography}{99}` 和 `\end{thebibliography}` 之间添加：
```latex
\bibitem{编号} 作者. 文献标题[J]. 期刊, 年, 卷(期): 页码.
```

## ⚠️ 注意事项

1. **编译器选择**：Overleaf建议使用 XeLaTeX 编译器
2. **中文字体**：模板使用系统自带中文字体，无需额外配置
3. **图表路径**：将图片放在与 main.tex 同一目录下，使用相对路径引用
4. **页码**：从正文开始计算页码

## 🎨 自定义修改

### 修改章节标题样式
在 `\titleformat` 部分修改格式。

### 修改页面边距
在 `\geometry` 部分修改。

### 修改行距
修改 `\linespread{1.5}` 中的数值。

## 📧 问题反馈

如有使用问题，请联系：
- Email: your@email.com

## ✅ 论文检查清单

提交论文前请检查：
- [ ] 封面信息完整正确
- [ ] 中英文摘要已填写
- [ ] 目录更新正确
- [ ] 章节编号连续
- [ ] 图表编号正确
- [ ] 参考文献格式规范
- [ ] 页码连续
- [ ] 格式符合学校要求

---
**祝顺利完成论文！** 🎓
