##概览##
>报告时间段：20130708-20130712


* 问题序号 id 结构从自增 id 修改为 Mongo id
* 时间格式 从 时间戳 修改为 年月日格式
* 答案导出-引用题目导出 优化及增加
* 下一步开发的功能的产品设计方案准备
* 与 IPSOS 问卷传输对接准备

##本周进展##


类别|工作详情|状态|负责人
---|:---|:---|:---|:---|:
问卷结构|问题序号 id 结构从自增 id 修改为 Mongo id|待验收|RD 刘强
时间存储|时间格式 从 时间戳 修改为 年月日格式|在开发|RD 刘强
答案导出-引用导出|增加其他排他选项的引用及多重引用的存储|在开发|PM 劲松 方婷 RD 黄轩宇  
产品功能方案设计|全站题号的展示方式统一设计 |待验收|PM 马倩  
与 IPSOS 问卷传输对接|通过事先约定的 FTP， 抓取问卷及答卷 |待验收|PM 劲松 RD 刘强  
BUG 修复|非管理员的用户使用人口属性模板问题|已完成|PM 马倩 RD 刘强  
业务支持|为 群邑 开通试用权限|开始|PM 劲松 方婷
##存在的问题##

* 引用功能涉及到多重引用，需要在技术实现以及方便使用上做一个平衡   
 `临时解决方案:实际引用多重，但是只提示引用上一层级，在实际业务上验收是否满足需求`


##需要业务方配合的事项##

* 新功能是否满足需求的评估。



##下周计划##

* 理顺与 IPSOS 的 panel 库合作投放问卷及回收流程
* 解析抓取到的 IPSOS 问卷，存成 Survey 可用的结构
* 答案导出-其他排他的引用测试上线
* 矩阵引用功能开发

