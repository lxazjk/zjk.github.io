# 欢迎来到我的技术博客

这里是关于 **C++ 高性能编程**、**MLSys (机器学习系统)** 以及 **操作系统内核** 的探索笔记。

---

## 👋 关于本站

!!! info "核心主题"
    本站主要记录我在底层系统开发过程中的学习与思考，内容涵盖：
    
    *   :material-language-cpp: **Modern C++** - 模板元编程、性能优化、并发模型
    *   :material-chip: **MLSys** - 推理引擎、算子优化 (CUDA/Triton)、编译器前端
    *   :material-linux: **OS & Kernel** - 内存管理、文件系统、虚拟化技术

## 🚀 代码风格展示

这是本站代码块的显示效果（带行号与标题栏）：

```cpp title="demo_kernel.cpp" linenums="1"
#include <iostream>
#include <vector>

// 模拟一个简单的向量加法
template <typename T>
void vector_add(const std::vector<T>& a, const std::vector<T>& b, std::vector<T>& c) {
    // 假设 a, b, c 大小一致
    for (size_t i = 0; i < a.size(); ++i) {
        c[i] = a[i] + b[i];
    }
}

int main() {
    std::cout << "Hello, MLSys!" << std::endl;
    return 0;
}
```