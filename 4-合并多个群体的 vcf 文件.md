

**合并全基因组重测序和芯片测序数据**
合并**检测群体 qmrb_50sheep_chr1to26.vcf.gz（test group）** 和 **参考群体 snp448.vcf.gz（source group）** 两个 vcf.gz 文件  
  
全基因组重测序 50 个体：qmrb_50sheep_chr1to26.vcf.gz，经 snp 质控和染色体编号重命名处理  
芯片测序 448 个体：snp448.vcf.gz，经 snp 质控和色体编号重命名处理  
  
- 避免样本id重复
- 保证染色体命名方式统一
- 保证同一参考基因组
- 查看染色体长度是否一致（侧面验证是否采用相同参考基因组或相同测序类型）


#### 1. qmrb_50sheep_chr1to26.vcf.gz
















































