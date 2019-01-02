title: 项目配置
---

## 系统可用高级变量

| 高级变量          | 备注                | 样例         |
| ----------------- | ------------------- | ------------ |
| `${BRANCH}`       | 当前部署分支        | master       |
| `${COMMIT_ID}`    | 当前部署的commit_id | abcde12      |
| `${PROJECT_NAME}` | 当前部署的项目名称  | 大数据平台   |
| `${PROJECT_ID}`   | 当前部署的项目id    | 12           |
| `${TASK_NAME}`    | 当前部署的任务名称  | 增加图表样式 |
| `${TASK_ID}`      | 当前部署的任务id    | 11           |
| `${ENVIRONMENT}`  | 当前部署所在的环境  | 测试环境     |
| `${DEPLOY_USER}`  | 当前部署的用户      | 吴水永       |
| `${DEPLOY_TIME}`  | 当前部署的时间      | 2019-01-01   |

## 自定义高级变量
```
# 在多个环节重复使用的变量

# 
```