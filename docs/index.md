# MkDocs 渲染示例

这个页面展示了 MkDocs 支持的各种格式渲染效果。

## 1. 数学公式

行内公式: $E = mc^2$

独立公式:
$$
\begin{aligned}
\frac{\partial f}{\partial x} &= 2x + y \\
\frac{\partial f}{\partial y} &= x + 2y
\end{aligned}
$$

## 2. 代码块

Python 代码示例:

```python
def hello_world():
    print("Welcome to MkDocs!")
    return True
```

## 3. 列表样式

### 普通列表
- 第一项
- 第二项
  - 子项 A
  - 子项 B

### 任务列表
- [x] 已完成任务
- [ ] 待办任务
- [ ] 计划任务

## 4. 引用和强调

> 这是一个引用示例
> 
> 可以包含多行内容

**重要内容**用粗体表示，*斜体*用于强调。

## 5. 表格示例

| 功能 | 支持情况 | 备注 |
|------|----------|------|
| 数学公式 | ✅ | 通过 MathJax |
| 代码高亮 | ✅ | 多语言支持 |
| 图表 | ✅ | Mermaid 支持 |

