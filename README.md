# ff14冒险者小队分队任务计算器
豆芽为了完成40级重要任务写的一点代码，自用的，没有前端，以命令行形式运行。
## 主要功能
对已有的冒险者小队队员（最多8位）及相应任务进行最优调度。
### 特色功能
1. 支持队员人数不足8人时的调度；
2. 支持多任务同步计算，计算出可以完成、训练后可完成、不能完成的结果，并给出任务完成推荐顺序；
3. 支持对需要训练才能完成的任务计算训练过程，**给出最少次数的训练路径**；
4. 支持指定某（些）队员必需执行任务，一般用于作用吉兆或练级；
5. 支持对结果的数量的过滤。
## 使用说明
1. 本代码在node环境下编写，可以使用任何支持的环境运行代码。（例如在线运行http://run.nodejs.cn/）
2. 根据实际，修改代码中数字标号的5项内容
3. 运行
## 更新说明
- v1.1：新增对不能完成的任务进行分类，给出属性两项达标、一项达标和不达标三类。
