# README

Obtained the raw `fastq.gz` files from https://www.mothur.org/MiSeqDevelopmentData.html
* Downloaded https://www.mothur.org/MiSeqDevelopmentData/StabilityNoMetaG.tar
* Ran the following from the project's root directory

```bash
wget --no-check-certificate https://www.mothur.org/MiSeqDevelopmentData/StabilityNoMetaG.tar
tar xvf StabilityNoMetaG.tar -C data/raw/
rm StabilityNoMetaG.tar
```
