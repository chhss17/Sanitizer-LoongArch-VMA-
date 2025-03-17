# 题目：Sanitizer动态支持LoongArch多种VMA（虚拟内存区域）配置

## 项目描述
在LLVM中，[Sanitizer](https://compiler-rt.llvm.org/)是一组用于检测和诊断C/C++代码中潜在错误的工具，帮助开发者提高代码的质量和稳定性。目前上游的Sanitizer在LoongArch架构上仅支持47位VMA（Virtual Memory Area，虚拟内存区域），本项目目标是增加其他常见的VMA支持（例如40位），并根据实际运行环境动态自适应。参与本项目能够加深对计算机系统底层原理的理解，掌握开源项目开发与协作等方面的知识，还能显著提升编程技能、调试能力及对复杂系统的掌控力。

## 参赛要求
* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师
* 陆伟宁  luweining@loongson.cn

## 难度：中-高

## License：Apache License v2.0 with LLVM Exceptions.

## 预期目标

* 能够通过compiler-rt回归测试，在不同VMA环境下运行正常。
* 将代码提交到LLVM上游社区。

## 参考资源

* [龙芯相关大赛参考文档](https://github.com/LoongsonLab/oscomp-documents)

## 备注
* 提供新世界内核版本的龙芯云资源
