---
title: Markdown 综合功能测试
date: 2026-02-19 12:22:01
tags: 
  - Test
  - Hexo
categories: 
  - Demo
---

这是一篇用于测试 Hexo 主题渲染能力的示例文章。涵盖了代码高亮、数学公式、图表、引用等常用功能。

<!-- more -->

## 1. 代码高亮测试

### JavaScript (ES6)
```javascript
const fibonacci = (n) => {
  if (n <= 1) return n;
  return fibonacci(n - 1) + fibonacci(n - 2);
};

console.log('Fibonacci(10):', fibonacci(10));
```

### Python
```python
def greet(name):
    """一个简单的打招呼函数"""
    return f"Hello, {name}! Welcome to Hexo."

if __name__ == "__main__":
    print(greet("LeNotFound"))
```

### C++
```cpp
#include <iostream>
#include <vector>

int main() {
    std::vector<int> nums = {1, 2, 3, 4, 5};
    for(int n : nums) {
        std::cout << "Number: " << n << std::endl;
    }
    return 0;
}
```

---

## 2. 数学公式 (LaTeX)

> 注意：如果公式未正常显示，请检查是否安装了 `hexo-filter-mathjax` 或类似的数学公式插件。

### 行内公式
勾股定理：$a^2 + b^2 = c^2$

### 块级公式
$$
E = mc^2
$$

$$
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

$$
\int_{0}^{\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$

---

## 3. 表格测试

| 功能 | 状态 | 备注 |
| :--- | :---: | :--- |
| 代码高亮 | ✅ 已支持 | 支持多种主流语言 |
| 数学公式 | ❓ 待确认 | 需插件支持 |
| 任务列表 | ✅ 已支持 | GFM 标准 |
| 响应式设计 | ✅ 已支持 | 适配移动端 |

---

## 4. 任务列表

- [x] 完成 Hexo 初始化
- [x] 解决依赖安全漏洞 (minimatch)
- [x] 转换 Tux2.png 为 ICO
- [ ] 撰写第一篇正式博文
- [ ] 配置自动部署

---

## 5. 引用与样式

### 引用
> “Stay hungry, stay foolish.” —— Steve Jobs

### 脚注
这是一个带脚注的句子[^1]。

[^1]: 这是一个示例脚注，用于解释某些术语。

---

## 6. 图片测试

![Tux2 预览](/assets/img/Tux2.png)
*注：图片路径需根据你的实际资源配置进行调整。*
