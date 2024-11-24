
### task2： 设计一个简单的投票统计器

1. 设计一个简单的投票统计器用于小团队内部投票，要求能累积统计出赞成票和反对票的票数
2. 考虑检查投票者属于团队成员，假设队员不会重复投票

请提交测试执行脚本。

**文件结构**
- Vote.ts 合约代码文件（主要采用MerkleMap来实现成员鉴权）
- Vote.test.ts 合约测试用例（测试了成员与非成员投赞成或反对和组合情况，以及测试了MerkleMap的Root的更新功能）