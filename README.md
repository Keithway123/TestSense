# TestSense
TestSense 是一个面向生产测试场景的分析助手，设计围绕五个场景进行：
- `Ask Production Data` **查询生产数据** -> 自然语言访问企业数据\
eg:
    1. “META001 最近 10 次 Bluetooth Test 结果是什么？”
    2. “今天 Station03 的 Bluetooth 失败执行次数是多少？”
    3. “今天 Bluetooth 失败最多的 5 个 Error Code 是什么？”

- `Analyze Yield` **良率异常分析** -> 从数据中发现问题\
eg:“为什么今天 Bluetooth 良率从 98% 掉到 91%？”

- `Diagnose Failure` **故障定位** -> 缩短 Debug / Troubleshooting 时间\
eg:“为什么 FAIL？下一步应该查什么？”

- `Search Knowledge` **建立可问答企业知识** -> 把企业隐性知识变成可搜索、可复用的知识资产\
eg：“这个 Error Code 怎么处理？”

- `Analyze Log` **解析日志** -> 自动化 Debug 和日志分析\
eg：解析测试日志，定位 FAIL Step，并给出候选原因与下一步验证建议。

## 项目阶段
当前阶段: Python 项目初始化。
