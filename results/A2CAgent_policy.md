# A2CAgent 最优选课策略

该文件展示了经过训练的Agent在面对所有课程时，所做出的最优出价决策。

### Agent的课程偏好分布
- **最喜欢**: `[7, 3, 11, 9]`
- **中等喜好**: `[24, 17, 13, 2, 14, 10, 4, 20]`
- **不喜欢**: `[19, 5, 18, 21, 6, 23, 12, 8, 0, 15, 1, 16, 22]`

### 详细决策过程

| 课程 ID | 课程类型 | 决策时剩余积分 | Agent决策 (出价) |
|:---:|:---:|:---:|:---:|
| 0 | 不喜欢 | 100 | **30** |
| 1 | 不喜欢 | 70 | **30** |
| 2 | 中等喜好 | 40 | **30** |
| 3 | 最喜欢 | 10 | **0** |
| 4 | 中等喜好 | 10 | **0** |
| 5 | 不喜欢 | 10 | **0** |
| 6 | 不喜欢 | 10 | **0** |
| 7 | 最喜欢 | 10 | **0** |
| 8 | 不喜欢 | 10 | **0** |
| 9 | 最喜欢 | 10 | **0** |
| 10 | 中等喜好 | 10 | **0** |
| 11 | 最喜欢 | 10 | **0** |
| 12 | 不喜欢 | 10 | **0** |
| 13 | 中等喜好 | 10 | **0** |
| 14 | 中等喜好 | 10 | **0** |
| 15 | 不喜欢 | 10 | **0** |
| 16 | 不喜欢 | 10 | **0** |
| 17 | 中等喜好 | 10 | **0** |
| 18 | 不喜欢 | 10 | **0** |
| 19 | 不喜欢 | 10 | **0** |
| 20 | 中等喜好 | 10 | **0** |
| 21 | 不喜欢 | 10 | **0** |
| 22 | 不喜欢 | 10 | **0** |
| 23 | 不喜欢 | 10 | **0** |
| 24 | 中等喜好 | 10 | **0** |
