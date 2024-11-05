1.At this URL, the datas are available:

https://figshare.com/s/fd7276e3583b457bd61d

1. Sample sheet file (gdc_sample_sheet.tsv)
2. Manifest file (gdc_manifest.txt)
3. Gene expression data (tcga_data.tar.gz)

The command: tar -zxvf tcga_data.tar.gz is ran to unzip to get the datas and then following snakemake is ran to obtain the results required .
   
2.  create a function to pull out, the directory name and the respecteive tpm value for the given gene (rule 1).

3. Then read those directory's names in such a way that it creates a file where the tpm are sorted as, normal and tumor according to the data from gdc_sample_sheet.tsv, this is our rule2.

4.  Then, plot a box_plot using R by reading the file from rule 2.
