# temporal 学习
## 为什么使用工作流
   工作流的本质是推动状态流转和状态持久化，对于计算资源的管理不是专业的
## 工作流的特性
   - 流程的逻辑控制和可编排性
   - 流转状态的持久化和可视化
   - 节点功能的自由度
   - 分布式异步执行能力

## 适用场景
## 概念
- **tempor server**:  
- **namespace**: namespace是temporal中的隔离单元,可用于区分环境,如dev,prd等，也可以用于区分不同团队，避免相互影响。如果不指定namespace，则使用默认的“default”。大小写敏感,建议使用小写
创建方式: tctl    --namespace autohealer   namespace register
- **workflow**:
  workflowID: namespece内唯一

- **activity**:
- **starter**:
- **worker**:
- 