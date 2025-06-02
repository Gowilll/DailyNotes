# Markdown 基础语法速查表

| 功能         | 语法示例                                             | 显示效果                         |
|--------------|------------------------------------------------------|----------------------------------|
| **标题**     | `# 一级标题`<br>`## 二级标题`<br>`### 三级标题`       | 一级标题<br>二级标题<br>三级标题 |
| **加粗**     | `**加粗**`                                            | **加粗**                         |
| **斜体**     | `*斜体*`                                              | *斜体*                           |
| **加粗+斜体**| `***加粗斜体***`                                      | ***加粗斜体***                   |
| **删除线**   | `~~删除线~~`                                          | ~~删除线~~                       |
| **引用**     | `> 引用内容`<br>`>> 嵌套引用`                          | > 引用内容<br>> 嵌套引用         |
| **无序列表** | `- 项目1`<br>`- 项目2`                                | - 项目1<br>- 项目2              |
| **有序列表** | `1. 第一项`<br>`2. 第二项`                             | 1. 第一项<br>2. 第二项           |
| **链接**     | `[点击这里](https://example.com)`                    | [点击这里](https://example.com) |
| **图片**     | `![描述](https://example.com/image.jpg)`             | 显示图片                         |
| **行内代码** | `` `代码` ``                                          | `代码`                           |
| **代码块**   | \`\`\`python<br>print("Hello")<br>\`\`\`             | 格式化代码块                     |
| **分割线**   | `---` 或 `***`                                        | ---（分割线）                   |
| **表格**     | `|列1|列2|`<br>`|--|--|`<br>`|A|B|`                   | 表格形式                         |
| **任务列表** | `- [ ] 未完成`<br>`- [x] 已完成`                      | - [ ] 未完成<br>- [x] 已完成     |
| **转义字符** | `\*不强调\*`                                          | \*不强调\*（显示星号）          |

---
一、换行
- **段落换行**：空一行（即按两次 Enter）
- **强制换行**：在行尾加两个空格再按 Enter  
- **使用 `<br>` 标签**：适用于 HTML 语法  
二、目录
- [换行说明](#换行说明github-中换行问题)
- [Markdown 基础语法](#markdown-基础语法一览表)
- [GitHub 特性](#github-markdown-独有功能)

 [★ pandas的Series](#pandas的Series对象)  
 [★ pandas的DataFrame对象](#pandas的DataFrame对象)  
 [★ pandas的Index对象](#pandas的Index对象)  
---

## 📘 目录  
 [★ pandas的Series](#pandas的Series对象)  
 [★ pandas的DataFrame对象](#pandas的DataFrame对象)  
 [★ pandas的Index对象](#pandas的Index对象)  
---
> pandas是在Numpy基础上建立的新程序库，提供了一种高效的DataFrame数据结构。DataFrame本质上是一种带行标签和列标签、支持异构数据类型和缺失值的多维数组。
> 查看pandas版本号
> ```python
> import pandas as pd
> pd.__verson__
> ```
> pandas的别名是pd

## pandas的Series对象  
学习pandas先看3个基本数据结构：series、dataframe和indes。  
先从导入标准Numpy和pandas开始：  
```python
import numpy as np
import pandas as pd
```
