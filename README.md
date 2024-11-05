1.At this URL, the datas are available:

https://figshare.com/s/fd7276e3583b457bd61d

1. Sample sheet file (gdc_sample_sheet.tsv)
2. Manifest file (gdc_manifest.txt)
3. Gene expression data (tcga_data.tar.gz)

The command: tar -zxvf tcga_data.tar.gz is ran to unzip to get the datas and then following snakemake is ran to obtain the results required .
   
2.  create a function to pull out, the directory name and the respected tpm value.
3. Then read the directories to create a file where the tpm are sorted as, normal and tumor.
4. Then, plot a box_plot using R.
