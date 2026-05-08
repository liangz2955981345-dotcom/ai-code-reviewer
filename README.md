# ai-code-reviewer
AI Code Reviewer 是一个基于多Agent协作架构的代码审查与优化平台，通过四个专业Agent（CodeParser、SecurityAudit、PerformanceOptimizer、StyleChecker）按优先级顺序协同工作，结合长链推理能力对代码进行全方位分析——从AST结构解析、安全漏洞扫描（检测命令注入、SQL注入、硬编码凭证等10+种风险模式）、算法复杂度分析，到PEP 8规范检查和代码风格评估。各Agent共享上下文并记录完整推理链，最终生成带具体行号和可执行修复建议的综合报告，帮助开发者在上线前发现并解决潜在的安全隐患、性能瓶颈和代码规范问题。
