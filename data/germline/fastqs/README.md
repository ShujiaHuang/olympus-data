time samtools sort -n ../bams/mother.bam | bamToFastq -i - -fq NA12878_1.fastq -fq2 NA12878_2.fastq
bgzip NA12878_1.fastq
bgzip NA12878_2.fastq
time samtools sort -n ../bams/father.bam | bamToFastq -i - -fq NA12877_1.fastq -fq2 NA12877_2.fastq
