# Bioinformatics-Project
The purpose oof this is to run PCA on alleles and to hone bioinformatics project skills.
* Download a VCF of population genotypes from the 1000 Genomes project.
* Use pysam to parse it and summarize it into a 2D numpy array to run PCA and save it as a pandas dataframe.
* Run PCA and tSNE on it and visualize the results with both matplotlib and Altair, coloring the points based on the ancestry labels.

## Preview VCF on 42basepairs

* [Preview variants](https://42basepairs.com/browse/s3/1000genomes/release/20110521?file=ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz&preview=variants)
* [Subsample variants](https://42basepairs.com/browse/s3/1000genomes/release/20110521?file=ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz&preview=subsample&loci=22%3A16000000-16100000)


## Download data files on the command line

```bash
# Download from 42basepairs
curl -O "https://42basepairs.com/download/s3/1000genomes/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz"

curl -O "https://42basepairs.com/download/s3/1000genomes/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz.tbi"

curl -O "https://42basepairs.com/download/s3/1000genomes/release/20110521/phase1_integrated_calls.20101123.ALL.panel"

# or use "wget" instead of "curl -O" if you don't have curl.
```
## Results
The phtyon scrpit is included, as well as the colab notebook link that has plotted graphs

## Colab notebook:
https://colab.research.google.com/drive/1tFTFYG4ZIFVwkwgUVRlN1e2TQG6Hzc0K?authuser=4#scrollTo=dBhjsU5VkIQx
## Special Thanks
Special Thanks to Maria Nattestad for this project!


