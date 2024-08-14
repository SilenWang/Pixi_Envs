## 环境内软件一览

- wes
    + fastqc
    + fastp
    + multiqc
    + bwa
    + samtools
    + bedtools
    + bcftools
    + gatk4
    + ensembl-vep
    + snpeff
    + CNVkit
    + gistic2
    + maftools
    + ggplot2
    + ggpubr
- rnaseq
    + star
    + hisat2
    + htseq
    + subread
    + limma
    + deseq2
    + clusterProfiler
    + signatureanalyzer
    + ggplot2
    + ggpubr
- dipseq
    + bowtie2
    + macs2
    + deeptools
- common
    + snakemake
    + igv
    + sra-tools
- pydata
    + numpy
    + pandas
    + statsmodels
    + scipy

## 环境内软件使用

- 直接使用: 使用 `pixi run -e [环境名] [待运行的命令]` 可以直接在环境内调用相应的软件
- 进入环境后使用: `pixi shell -e [环境名]`进入对应环境后，可直接使用对应的软件

## MutSig2CV特别说明

该软件是matlab的扩展，安装较为复杂，还在调试种，除该软件外的其他软件均已安装完成