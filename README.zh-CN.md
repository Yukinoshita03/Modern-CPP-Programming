# 现代 C++ 编程

语言：[English](README.md) | 简体中文

## C++03 / C++11 / C++14 / C++17 / C++20 / C++23 / C++26

这是一门开放访问课程，面向已经熟悉 C 语言和面向对象编程、希望达到熟练 C++ 编程水平的学习者。课程从 C++ 编程基础讲起，并逐步深入到高级 C++ 语义和概念。

**主要特点**：

- 免费，并且频繁更新
- 29 讲，2000 多页幻灯片
- 包含最新语言标准中的概念和特性
- 注重实践教学：用简洁、结构化的说明配合代码讲解
- 使用最小代码示例，聚焦展示某个具体特性或问题
- 涵盖互补的语言相关主题：工具、代码规范、项目组织和代码优化
- 基于实践经验：许多内容、示例和问题来自作者作为软件工程师工作中遇到的真实案例

如果你喜欢这门课程，或觉得它有帮助，请给原项目加一个 Star：

[![stars - Modern-CPP-Programming](https://img.shields.io/github/stars/federico-busato/Modern-CPP-Programming?style=social)](https://github.com/federico-busato/Modern-CPP-Programming)

**路线图**：

1. 从 LaTeX 迁移到 [Typst](https://typst.app/)。
2. 完全开源课程材料，并允许直接贡献。

## 目录

- [章节](#章节)
- [详细主题](#详细主题)
- [报告问题与贡献](#报告问题与贡献)
- [课程使用情况](#课程使用情况)
- [许可证](#许可证)
- [作者](#作者)

## 章节

| # | 标题 | 主要内容 |
| --- | --- | --- |
| **1** | [**Introduction / 介绍**](01.Introduction.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/01.Introduction.html)) | C/C++ 历史、应用领域、课程介绍 |
| **2** | [**Preparation / 准备工作**](02.Preparation.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/02.Preparation.html)) | 书籍、如何编译、Hello world |
| **3** | [**Basic Concepts I / 基础概念 I**](03.Basic_Concepts_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/03.Basic_Concepts_I.html)) | 类型系统、基本类型和运算符 |
| **4** | [**Basic Concepts II / 基础概念 II**](04.Basic_Concepts_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/04.Basic_Concepts_II.html)) | 整数类型和算术 |
| **5** | [**Basic Concepts III / 基础概念 III**](05.Basic_Concepts_III.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/05.Basic_Concepts_III.html)) | 浮点类型和算术 |
| **6** | [**Basic Concepts IV / 基础概念 IV**](06.Basic_Concepts_IV.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/06.Basic_Concepts_IV.html)) | 实体、枚举、结构体、控制流语句 |
| **7** | [**Basic Concepts V / 基础概念 V**](07.Basic_Concepts_V.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/07.Basic_Concepts_V.html)) | 堆、栈、指针、引用、const 属性、转换运算符 |
| **8** | [**Basic Concepts VI / 基础概念 VI**](08.Basic_Concepts_VI.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/08.Basic_Concepts_VI.html)) | 函数、Lambda 表达式、预处理指令 |
| **9** | [**Object-Oriented Programming I / 面向对象编程 I**](09.Object_Oriented_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/09.Object_Oriented_I.html)) | 类层次、构造函数、析构函数、类关键字 |
| **10** | [**Object Oriented Programming II / 面向对象编程 II**](10.Object_Oriented_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/10.Object_Oriented_II.html)) | 多态、运算符重载 |
| **11** | [**Templates and Meta-programming I / 模板与元编程 I**](11.Templates_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/11.Templates_I.html)) | 函数模板、类型特征、编译期工具 |
| **12** | [**Templates and Meta-programming II / 模板与元编程 II**](12.Templates_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/12.Templates_II.html)) | 类模板、SFINAE |
| **13** | [**Translation Units I / 翻译单元 I**](13.Translation_Units_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/13.Translation_Units_I.html)) | 链接与单一定义规则 |
| **14** | [**Translation Units II / 翻译单元 II**](14.Translation_Units_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/14.Translation_Units_II.html)) | 多翻译单元和文件、`#include`、模块 |
| **15** | [**Code Conventions I / 代码规范 I**](15.Code_Convention_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/15.Code_Convention_I.html)) | 项目组织、代码规范简介、实体约定 |
| **16** | [**Code Conventions II / 代码规范 II**](16.Code_Convention_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/16.Code_Convention_II.html)) | 模板、命名空间、现代 C++、可维护性、命名和格式约定 |
| **17** | [**Debugging and Testing / 调试与测试**](17.Debugging.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/17.Debugging.html)) | 执行/内存调试、Sanitizer、加固技术、单元测试、测试驱动开发 |
| **18** | [**Ecosystem / 生态系统**](18.Ecosystem.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/18.Ecosystem.html)) | CMake、文档和其他工具 |
| **19** | [**Utilities / 工具库**](19.Utilities.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/19.Utilities.html)) | 主要 `std` 库 |
| **20** | [**Containers, Iterators, and Algorithms / 容器、迭代器与算法**](20.Iterators_Containers_Alg.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/20.Iterators_Containers_Alg.html)) | 容器、迭代器、算法、Ranges |
| **21** | [**Advanced Topics I / 高级主题 I**](21.Advanced_Topics_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/21.Advanced_Topics_I.html)) | 移动语义、万能引用、类型推导 |
| **22** | [**Advanced Topics II / 高级主题 II**](22.Advanced_Topics_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/22.Advanced_Topics_II.html)) | 错误处理、C++ 惯用法、智能指针 |
| **23** | [**Performance Optimizations I / 性能优化 I**](23.Optimization_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/23.Optimization_I.html)) | Amdahl 定律、性能边界、架构概念（ILP、SIMD 等）、内存层级 |
| **24** | [**Performance Optimizations II / 性能优化 II**](24.Optimization_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/24.Optimization_II.html)) | 算术优化、内存优化等 |
| **25** | [**Performance Optimizations III / 性能优化 III**](25.Optimization_III.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/25.Optimization_III.html)) | 编译器优化、性能分析、基准测试工具 |
| **26** | [**Software Design I / 软件设计 I**](26.Software_Design_I.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/26.Software_Design_I.html)) | 基础概念、原则、使用场景 |
| **27** | [**Software Design II / 软件设计 II**](27.Software_Design_II.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/27.Software_Design_II.html)) | 设计模式和惯用法 |
| **28** | [**Binary Size / 二进制体积**](28.Binary_Size.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/28.Binary_Size.html)) | 二进制体积相关主题 |
| **29** | [**Build Time / 构建时间**](29.Build_time.pdf) ([html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/29.Build_time.html)) | 构建时间相关主题 |

**合集书籍**：[**modern-cpp.pdf**](modern-cpp.pdf)（可能比最新提交落后几个版本），[html](https://federico-busato.github.io/Modern-CPP-Programming/htmls/modern-cpp.html)

## 详细主题

**[1. Introduction / 介绍](01.Introduction.pdf)**

- C/C++ 编程语言简史
- 应用领域与流行度
- C++ 哲学
- C++ 弱点：C++ 替代语言、为什么迁移到新语言很难
- 课程介绍

**[2. Preparation / 准备工作](02.Preparation.pdf)**

- 书籍与参考资料
- 幻灯片图例
- 应该使用什么编辑器、IDE 或编译器
- 如何编译
- Hello World：I/O Stream

**[3. Basic Concepts I - Type System, Fundamental Types, and Operators / 基础概念 I：类型系统、基本类型和运算符](03.Basic_Concepts_I.pdf)**

- C++ 类型系统：类型分类、类型属性
- C++ 基本类型概览：算术类型、非标准算术类型、`void` 类型、`nullptr`
- `auto` 关键字
- C++ 运算符：运算符优先级、前置/后置自增自减语义、赋值、复合赋值和逗号运算符、三路比较运算符 `<=>`

**[4. Basic Concepts II - Integral Types / 基础概念 II：整数类型](04.Basic_Concepts_II.pdf)**

- 整数数据类型：后缀和前缀、固定位宽整数、`size_t`、`ptrdiff_t`、`uintptr_t`
- 算术运算语义：饱和算术
- 整数未定义行为：有符号溢出及其他情况
- 整数转换规则：相同大小转换、整数转换规则、算术运算提升规则、安全比较函数、算术运算特殊情况

**[5. Basic Concepts III - Floating-point Types / 基础概念 III：浮点类型](05.Basic_Concepts_III.pdf)**

- 浮点类型：后缀、IEEE 浮点标准和其他表示、正规/非正规值、无穷、非数值（`NaN`）、机器精度、末位单位（ULP）、速查表、限制和实用函数、算术属性、特殊值行为、未定义行为、检测浮点错误
- 浮点问题：灾难性抵消、浮点比较

**[6. Basic Concepts IV - Entities and Control Flow / 基础概念 IV：实体和控制流](06.Basic_Concepts_IV.pdf)**

- 实体
- 声明与定义
- 枚举
- `struct`、位域、`union`
- 控制流：`if`、`for`/`while`、基于范围的 `for`、`switch`、初始化语句、`goto`、避免未使用变量警告
- 命名空间：显式全局命名空间、命名空间别名、`using` 声明、`using namespace` 指令、`inline` 命名空间
- 属性：`[[nodiscard]]`、`[[indeterminate]]`、`[[maybe_unused]]`、`[[deprecated]]`、`[[noreturn]]`

**[7. Basic Concepts V - Memory Concepts / 基础概念 V：内存概念](07.Basic_Concepts_V.pdf)**

- 指针：指针操作、取地址运算符 `&`、`struct` 成员访问、`void` 指针、指针转换、指针算术、野指针和悬空指针
- 固定大小数组
- 引用
- 堆与栈：栈内存、`new`、`delete`、非分配 placement allocation、非抛出分配、内存泄漏
- 初始化：变量初始化、统一初始化、数组初始化、结构体初始化、结构化绑定、动态内存初始化
- `const` 和常量表达式：常量和字面量、`const`、`constexpr`、`constexpr` 变量、`constexpr` 函数、`constexpr` 对象、`consteval`、`constinit`
- 条件常量表达式：`if constexpr`、`std::is_constant_evaluated()`、`if consteval`
- `volatile` 关键字
- 显式类型转换：`static_cast`、`const_cast`、`reinterpret_cast`、类型双关、`std::bit_cast`、统一初始化转换、`gsl::narrow_cast`
- `sizeof` 和 `alignof` 运算符：作用于 `struct` 的行为、`[[no_unique_address]]`

**[8. Basic Concepts VI - Functions and Preprocessing / 基础概念 VI：函数和预处理](08.Basic_Concepts_VI.pdf)**

- 函数：按值传递、按指针传递、按引用传递、函数签名和重载、重载与 `=delete`、默认参数
- 函数指针和函数对象
- Lambda 表达式：捕获列表、Lambda 与函数的关系、参数说明、可组合性、递归、`constexpr`/`consteval`、`template`、`mutable`、捕获列表与类
- 预处理：预处理器、常见错误、源码位置宏、条件编译宏、字符串化运算符（`#`）、`#error` 和 `#warning`、`#pragma`、记号粘贴运算符 `##`、可变参数宏

**[9. Object-Oriented Programming I - Class Concepts / 面向对象编程 I：类概念](09.Object_Oriented_I.pdf)**

- C++ 类：RAII 惯用法
- 类层次
- 访问说明符：继承访问说明符、数据成员什么时候用 `public`/`protected`/`private`
- 类构造函数：默认构造函数、类初始化、对象的统一初始化、委托构造函数、`explicit` 关键字
- 拷贝构造函数
- 类析构函数
- 默认化的构造函数、析构函数和运算符（`= default`）
- 类关键字：`this`、`static`、`const`、`mutable`、`using`、`friend`、`delete`

**[10. Object-Oriented Programming II - Polymorphism and Operator Overloading / 面向对象编程 II：多态与运算符重载](10.Object_Oriented_II.pdf)**

- 多态：C++ 多态机制、`virtual` 方法、虚表、`override`、`final`、常见错误、纯虚方法、抽象类和接口
- 继承转换与运行时类型识别
- 运算符重载：概览、比较运算符 `<`、三路比较 `<=>`、下标运算符 `[]`、多维下标、函数调用运算符 `()`、静态 `[]` 和 `()`、转换运算符 `T()`、返回类型重载解析、自增/自减、赋值、流运算符 `<<`、运算符注意事项
- C++ 对象布局：聚合、平凡类、标准布局类、POD、层次结构

**[11. Templates and Meta-programming I / 模板与元编程 I](11.Templates_I.pdf)**

- 函数模板：概览、模板实例化、模板参数、默认模板参数、重载、特化
- 变量模板
- 模板参数类型：泛型类型说明、`auto` 占位符、函数类型
- 编译期工具：`static_assert`、`using`、`decltype`
- 类型特征：概览、类型特征库、类型操作

**[12. Templates and Meta-programming II / 模板与元编程 II](12.Templates_II.pdf)**

- 类模板：类特化、类模板构造函数
- 构造函数模板实参自动推导（CTAD）
- 类模板高级概念：类+函数特化、依赖名中的 `typename` 和 `template`、类模板层次与 `using`、`friend`、模板模板参数
- 模板元编程
- SFINAE：替换失败不是错误，包括函数 SFINAE 和类 SFINAE
- 可变参数模板：同质可变参数、折叠表达式、可变参数类模板
- C++20 Concepts：概览、`concept`、`requires` 子句、`requires` 表达式、嵌套 `requires`
- 模板调试

**[13. Translation Units I / 翻译单元 I](13.Translation_Units_I.pdf)**

- 基础概念：翻译单元、局部和全局作用域、链接、可见性
- 存储类和存储期：存储期、存储类、`static`、匿名命名空间、`extern`
- `const` 和 `constexpr` 的链接：静态初始化顺序问题
- 链接总结
- 处理多个翻译单元：跨翻译单元的类
- 单一定义规则（ODR）：全局变量问题、ODR 第 3 点、`inline` 函数/变量、`constexpr` 与 `inline`
- 函数模板中的 ODR：案例、`extern`
- 类模板中的 ODR：案例、`extern`
- ODR 未定义行为与总结

**[14. Translation Units II / 翻译单元 II](14.Translation_Units_II.pdf)**

- `#include` 问题：include guard、前向声明、循环依赖、常见链接错误
- C++20 模块：概览、术语、可见性和可达性、模块单元类型、关键字、全局模块片段、私有模块片段、头模块单元、模块分区
- 编译多个翻译单元：基本编译器标志、编译方法
- C++ 库：静态库、构建和使用静态库、动态库、构建和使用动态库、ABI、反修饰、查找动态库依赖、分析目标文件/可执行文件符号

**[15. Code Conventions I / 代码规范 I](15.Code_Convention_I.pdf)**

- C++ 项目组织：项目目录、项目文件、常见项目组织说明、替代的 canonical 组织方式
- 编码风格和约定：概览、流行编码风格
- 头文件和 `#include`：include guard、`#include` 语法、包含顺序、常见头/源文件命名约定
- 预处理：宏、预处理语句
- 变量：`static` 全局变量、转换
- 枚举
- 算术类型：有符号与无符号整数、整数转换、整数类型大小和其他问题、浮点类型
- 函数：函数参数、函数实参、函数返回值、函数说明符、Lambda 表达式
- 结构体和类：`struct` 与 `class`、初始化、花括号初始化列表、特殊成员函数、`=default`、`=delete`、其他问题、继承、风格

**[16. Code Conventions II / 代码规范 II](16.Code_Convention_II.pdf)**

- `auto`
- 模板和类型推导
- 控制流：冗余控制流、`if/else`、比较、`switch`、`for/while`
- 命名空间：`using namespace` 指令、匿名/未命名命名空间、命名空间和类设计、风格
- 现代 C++ 特性：关键字、特性、类、库
- 可维护性：代码理解、函数、模板和推导、库
- 可移植性
- 命名：实体、变量、函数、风格约定、命名风格强制检查
- 可读性和格式：水平间距、指针/引用、垂直间距、花括号、类型修饰、减少代码冗长、其他问题
- 代码文档：函数文档、注释语法、文件文档

**[17. Debugging and Testing / 调试与测试](17.Debugging.pdf)**

- 调试概览：错误、缺陷和故障、软件缺陷成本、软件缺陷分类、程序错误和分类、软件缺陷分析
- 断言：运行时断言、契约、`std::stacktrace`
- 执行调试：断点、观察点/捕获点、控制流、栈和信息、打印、反汇编、`std::breakpoint`
- 内存调试：`valgrind`
- 加固技术：栈使用、标准 C 库加固、标准 C++ 库加固、未定义行为防护、控制流防护
- Sanitizer：AddressSanitizer、LeakSanitizer、MemorySanitizer、UndefinedBehaviorSanitizer、TypeSanitizer、采样型 sanitizer
- 调试总结
- 编译器警告
- 静态分析：编译器提供的静态分析器、开源静态分析器、专有静态分析器
- 代码测试：单元测试、测试驱动开发（TDD）、代码覆盖率、模糊测试
- 代码质量：`clang-tidy`
- 代码复杂度：圈复杂度、认知复杂度

**[18. Ecosystem / 生态系统](18.Ecosystem.pdf)**

- CMake：`cmake` 和 `ctest`
- 代码文档：`doxygen` 及替代工具
- 在线工具：AI 代码补全/IDE、编译和执行、代码转换、代码基准测试、代码搜索引擎
- 离线工具：代码格式化、代码统计、AST diff、项目可视化、本地代码搜索、AST 搜索、编程字体

**[19. Utilities / 工具库](19.Utilities.pdf)**

- View 介绍和 `std::span`
- `std::mdspan`
- 字符串和 `std::print`：`std::string`、数值转换、`std::string_view`、`std::format`、`std::print`
- 数学库：`<cmath>`、`<limits>`、`<numbers>`
- 随机数：基础概念、C++ `<random>`、种子、PRNG 周期和质量、分布、近期算法和性能、拟随机、真随机数生成器（TRNG）
- 时间测量：墙上时间、用户时间、系统时间
- 标准库类模板：`std::pair`、`std::tuple`、`std::variant`、`std::optional`、`std::any`
- 文件系统库：查询方法、修改方法

**[20. Containers, Iterators, and Algorithms / 容器、迭代器与算法](20.Iterators_Containers_Alg.pdf)**

- 容器和迭代器：语义
- 序列容器：`std::array`、`std::vector`、`std::deque`、`std::list`、`std::forward_list`
- 关联容器：`std::set`、`std::map`、`std::multiset`
- 容器适配器：`std::stack`、`std::queue`、`std::priority_queue`
- 实现自定义迭代器
- 迭代器说明
- 迭代器工具方法：`std::advance`、`std::next`、`std::prev`、`std::distance`、容器访问方法、迭代器特征
- 算法库：`std::find_if`、`std::sort`、`std::accumulate`、`std::generate`、`std::remove_if`
- C++20 Ranges：核心概念、Range view、Range adaptor、Range factory、Range 算法、Range actions

**[21. Advanced Topics I / 高级主题 I](21.Advanced_Topics_I.pdf)**

- 移动语义：`lvalue` 和 `rvalue` 引用、移动语义、`std::move`、类声明语义
- 万能引用和完美转发：万能引用、引用折叠规则、完美转发
- 值类别
- `&`、`&&` 引用限定符和 `volatile` 重载
- 拷贝消除和 RVO
- 类型推导：按引用、按指针、按值传递、`auto` 推导、`auto(x)` decay-copy
- `const` 正确性

**[22. Advanced Topics II / 高级主题 II](22.Advanced_Topics_II.pdf)**

- 未定义行为：非法行为、平台相关行为、未指定行为、检测未定义行为
- 错误处理：可恢复错误处理、返回码、C++ 异常、自定义异常、`noexcept`、内存分配问题、返回码和异常总结、`std::expected`、其他错误处理方式
- 智能指针：`std::unique_ptr`、`std::shared_ptr`、`std::weak_ptr`
- 并发：线程方法、互斥量、原子、基于任务的并行

**[23. Optimization I - Basic Concepts / 优化 I：基础概念](23.Optimization_I.pdf)**

- 介绍：摩尔定律、摩尔定律的局限、优化的原因
- 基础概念：渐进复杂度、时间-内存权衡、开发周期、Amdahl 定律、吞吐量、带宽、延迟、性能边界、算术强度
- 基础架构概念：指令吞吐（IPC）、顺序和乱序执行、指令流水线、指令级并行（ILP）、Little 定律、数据级并行（DLP）和向量指令（SIMD）、线程级并行（TLP）、单指令多线程（SIMT）、RISC、CISC 指令集
- 内存层级：内存层级概念、内存局部性、核心间延迟和线程亲和性、内存顺序模型

**[24. Optimization II - Code Optimization / 优化 II：代码优化](24.Optimization_II.pdf)**

- I/O 操作：`printf`、内存映射 I/O、加速原始数据加载
- 内存优化：堆内存、栈内存、`constexpr` 与 `static constexpr`、缓存利用、内存对齐、内存预取
- 算术类型：数据类型、算术运算、转换、浮点、编译器 intrinsic、范围内取值、查找表
- 控制流：分支、分支提示 `[[likely]]` / `[[unlikely]]`、有符号/无符号整数、循环、循环提升、循环展开、断言、编译器提示 `[[assume]]`/`std::unreachable()`、递归
- 函数：函数调用成本、实参传递、函数内联、纯函数、常量函数、指针别名
- 面向对象编程
- 标准库和其他语言方面

**[25. Optimization III / 优化 III：非编码优化与基准测试](25.Optimization_III.pdf)**

- 编译器优化：关于编译器、编译器优化标志、浮点优化标志、链接器优化标志、架构标志、帮助编译器生成更好代码、Profile-guided optimization（PGO 和 AutoFDO）、后处理二进制优化器、多面体优化
- 编译器转换技术：基础转换、循环 unswitching、循环融合、循环裂变、循环交换、循环分块
- 库和数据结构
- 性能基准测试：测试什么、负载/数据集质量、指标评估
- 稳定性能测量：缓存行为、稳定 CPU 性能、多线程因素、操作系统因素、程序内存布局、测量开销、编译器优化
- 性能分析：`gprof`、`uftrace`、`callgrind`、`cachegrind`、Linux `perf`
- 并行计算：并发与并行、性能扩展、Gustafson 定律、并行编程语言

**[26. Software Design I / 软件设计 I（草稿）](26.Software_Design_I.pdf)**

- 书籍和参考资料
- 基础概念：抽象、接口和模块、类不变量
- 软件设计原则：关注点分离、低耦合高内聚、封装和信息隐藏、契约式设计、问题分解、代码复用
- 软件复杂度：软件熵、技术债
- SOLID 设计原则
- 类设计：类接口原则、成员函数与自由函数、命名空间函数与类静态方法
- BLAS GEMM 案例研究
- 拥有对象和视图
- 值语义与引用语义
- 全局变量

**[27. Software Design II / 软件设计 II（草稿）](27.Software_Design_II.pdf)**

- C++ 惯用法：零法则、三法则、五法则
- 设计模式：单例、PIMPL、CRTP、模板虚函数

**[28. Binary Size / 二进制体积](28.Binary_Size.pdf)**

- 二进制体积介绍
- 编译器和链接器技术：优化标志、调试和运行时信息标志、符号可见性、异常标志、链接器标志、链接时优化（LTO）、CMake 支持
- 编码方面：函数内联、函数可见性、模板、静态存储期、链接、多态类、异常、头文件包含
- 二进制体积工具：`nm`、`objdump`、`Bloaty`、可执行文件打包器

**[29. Build Time / 构建时间](29.Build_time.pdf)**

- 编译时间介绍：构建时间的重要性、构建时间长的原因
- 编译器方面：编译器标志、优化过的编译器构建
- C++ 标准版本
- 预编译头（PCH）
- 链接器方面：链接时优化（LTO）、ThinLTO、主要链接器、链接器标志
- Unity Build
- 降低构建时间的工具：`ninja`、编译缓存、分布式编译、RAM disk、`Include-What-You-Use (IWYU)`
- 函数内联
- 模板：模板元编程成本、`extern` template、`constexpr` 变量与模板结构 + `static` 数据成员、标签分发、折叠表达式、C++20 concepts、`auto`、`using` 类型别名
- 其他方面：C++20 模块、重载解析、其他代码因素、PIMPL、include guard 与 `#pragma once`、静态/动态链接、注释和格式、外部因素
- 构建时间分析工具：Clang 构建时间分析、`ninjatracing`、`Templight`、`Build Bench`、Visual Studio `CompileScore`、Visual Studio `C++ Build Insights`

## 报告问题与贡献

更多信息请参见 [CONTRIBUTING.md](CONTRIBUTING.md)。

注意：上游项目的贡献说明明确限制 AI 生成内容作为直接贡献。本 fork 中的中文本地化工作用于个人学习和汉化维护；如果未来向上游提交 PR，应遵守上游的贡献政策。

## 课程使用情况

**Modern C++ Programming** 课程创建于 2018 年，并被意大利 [University of Verona](https://www.univr.it/en/university) 采用。它被用于计算机科学本科和硕士课程，分别授课三年和两年。该课程也被用于 NVIDIA 实习生培训。

如果你已经采用这门课程，或有兴趣在某些场景中使用它，可以联系作者，以便作者记录使用情况。作者也愿意分享 LaTeX 源代码（Typst 版本将很快在 GitHub 上开源）。

## 许可证

本仓库采用双许可证：

- **课程内容**：所有文字材料、幻灯片和图片基于 [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE-CC-BY-SA.md) 授权。
- **源代码**：所有代码示例和脚本基于 [MIT License](LICENSE-MIT.md) 授权。

## 作者

`Federico Busato`，[federico-busato.github.io](https://federico-busato.github.io/)

- LinkedIn：[www.linkedin.com/in/federico-busato/](https://www.linkedin.com/in/federico-busato/)
- Bluesky：[fbusato.bsky.social](https://bsky.app/profile/fbusato.bsky.social)
