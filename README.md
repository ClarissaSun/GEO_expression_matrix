# GEO_expression_matrix
This is a sample project to conduct a thorough analysis on GSE42872


---------------------------------------------------------------------------------
# related links:

http://www.bio-info-trainee.com/2087.html GEO数据库挖掘系列知识分享课程
https://www.bilibili.com/video/av26731585/ 配套教学视频

# course structure:

第一讲：GEO，表达芯片与R

第二讲：从GEO下载数据得到表达量矩阵

第三讲：对表达量矩阵用GSEA软件做分析

第四讲：根据分组信息做差异分析

第五讲：对差异基因结果做GO/KEGG超几何分布检验富集分析

第六讲：指定基因分组boxplot指定基因list画热图

第七讲：根据差异基因list获取string数据库的PPI网络数据

第八讲：PPI网络数据用R或者cytoscape画网络图

第九讲：网络图的子网络获取

第十讲：hug genes如何找

----------------------------------------------------------------------------------


# 仓库概括
## 主要项目代码文件夹：

GSE42872_main，主要演示GEO数据库挖掘的标准6步骤
GSE11121_surivival，主要演示基于基因表达量分组的批量生存分析

## 六个任务项目文件夹：

task1-check-specific-genes ， 主要演示检查自己感兴趣的基因在多个GSE数据集表现情况

task2-lncRNA-mRNA-network ， 主要演示如何构建网络

task3-multiple-groups ， 主要演示，如果样本分组信息非常复杂该如何进行下游分析

task4-NPC， 主要演示GEO数据库挖掘的标准6步骤，跟GSE42872_main类似

task5-dynamic-network-biomarker，主要演示新的算法，超脱于GSE42872_main展示的GEO数据库挖掘的标准6步骤

task6-GEO-TCGA，主要演示如何结合TCGA数据库

## 两个额外补充项目文件夹：

airway_RNAseq，主要演示如果是RNA-seq得到的表达矩阵该如何分析，与传统芯片表达矩阵的异同
breast_cancer_meta-analysis ， 主要演示如何进行meta分析。
