https://www.kaggle.com/datasets/rajeshrampure/black-friday-sale

### 问题描述：

黑色星期五是美国感恩节后的星期五，通常被称为黑色星期五。感恩节在每年11月的第四个星期四庆祝。自1952年起，感恩节后的第二天被视为美国圣诞购物季的开始，尽管直到最近几十年，"黑色星期五"这个术语才变得广泛使用。许多商店在黑色星期五提供大力推广的促销活动，非常早就开门，比如午夜，甚至可能在感恩节当天就开始销售。对于零售店或电子商务企业来说，最大的挑战是选择产品价格，以便在销售结束时获得最大利润。我们的项目涉及根据历史零售店销售数据确定产品价格。在生成预测之后，我们的模型将帮助零售店确定产品的价格以获取更多利润。

一家零售公司“ABC Private Limited”想了解顾客对不同品类的各种产品的购买行为(具体而言，购买金额)。他们分享了上个月以来各种客户对选定的大批量产品的采购摘要。
该数据集还包含客户人口统计数据(年龄、性别、婚姻状况、城市类型、当前城市)、产品详细信息(productid和产品类别)以及上个月的总购买金额。

现在，他们想建立一个模型来预测客户对各种产品的购买量，这将有助于他们为不同产品的客户创建个性化的报价。

##### 任务：
1. 对BlackFriday.csv数据集进行综合分析
-- 分别对客户信息、产品信息进行描述
2. 建立销售预测模型
-- 特征工程
-- 多变量线性回归，ANOVA，Tukey’s HSD post hoc test
-- 决策树，随机森林，XGBoost
-- 网格搜索寻找最优模型
3. 结论
-- 模型评估
-- 特征重要性

#### 数据字典：

|变量名  |含义 |
-----|-----| 
|User_ID | User ID |
|Product_ID | Product ID |
|Gender | Sex of User |
|Age | Age in bins |
|Occupation | Occupation (Masked) |
|City_Category | Category of the City (A, B, C) |
|Stay_In_Current_City_Years | Number of years stay in current city |
|Marital_Status | Marital Status |
|Product_Category_1 | Product Category (Masked) |
|Product_Category_2 | Product may belong to other categories also (Masked) |
|Product_Category_3 | Product may belong to other categories also (Masked) |
|Purchase | Purchase Amount (Target Variable) |
