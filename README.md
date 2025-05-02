# Cable bacteria in Koljö Fjord
This repository describes the main scripts and the procedure followed to analyze the metatranscriptomic data of the manuscript: "**Unexpected Abundance of Cable Bacteria in Deep Anoxic Sediments Reveals a New Biogeochemical Niche**."

The objective of the data analysis was to investigate the presence of sulfide-oxidizing bacteria, specifically the so-called cable bacteria (marine genus _Candidatus_ Electrothrix), in the Kristineberg Bay and Koljö Fjord areas on the west coast of Sweden. Sampling was conducted in 2023, resulting in the collection of 36 samples. Six sediment layers at varying depths were sampled in triplicate at each location. A total of 18 sediment samples per site (36 in total) were subjected to RNA extraction and sequencing using a NovaSeqXPlus platform (NovaSeqXSeries Control Software 1.2.0.28691) configured for 2 × 150 bp. The vertical sediment profiles included 0-1, 1-3, 7-9, 9-11, 20-22, and 30-32 cm depths. Additionally, data from two locations in the Tvärminne Archipelago, situated in Southern Finland, designated as Offshore and Nearshore (Hermans et al., 2024), were used to compare places.
The raw data is availabe at: https://www.ncbi.nlm.nih.gov/bioproject/?term=(PRJNA1253322)%20AND%20bioproject_sra[filter]%20NOT%20bioproject_gap[filter]

## The data analysis was broken down as follows:

**Samples:**

*Kristineberg Bay samples:*

	- P30612_101_S332_L005_R1_001.fastq.gz
	- P30612_101_S332_L005_R2_001.fastq.gz
	- P30612_102_S333_L005_R1_001.fastq.gz
	- P30612_102_S333_L005_R2_001.fastq.gz
	- P30612_103_S334_L005_R1_001.fastq.gz
	- P30612_103_S334_L005_R2_001.fastq.gz
	- P30612_104_S335_L005_R1_001.fastq.gz
	- P30612_104_S335_L005_R2_001.fastq.gz
	- P30612_105_S336_L005_R1_001.fastq.gz
	- P30612_105_S336_L005_R2_001.fastq.gz
	- P30612_106_S337_L005_R1_001.fastq.gz
	- P30612_106_S337_L005_R2_001.fastq.gz
	- P30612_107_S338_L005_R1_001.fastq.gz
	- P30612_107_S338_L005_R2_001.fastq.gz
	- P30612_108_S339_L005_R1_001.fastq.gz
	- P30612_108_S339_L005_R2_001.fastq.gz
	- P30612_109_S340_L005_R1_001.fastq.gz
	- P30612_109_S340_L005_R2_001.fastq.gz
	- P30612_110_S341_L005_R1_001.fastq.gz
	- P30612_110_S341_L005_R2_001.fastq.gz
	- P30612_111_S342_L005_R1_001.fastq.gz
	- P30612_111_S342_L005_R2_001.fastq.gz
	- P30612_112_S343_L005_R1_001.fastq.gz
	- P30612_112_S343_L005_R2_001.fastq.gz
	- P30612_113_S344_L005_R1_001.fastq.gz
	- P30612_113_S344_L005_R2_001.fastq.gz
	- P30612_114_S345_L005_R1_001.fastq.gz
	- P30612_114_S345_L005_R2_001.fastq.gz
	- P30612_115_S346_L005_R1_001.fastq.gz
	- P30612_115_S346_L005_R2_001.fastq.gz
	- P30612_116_S347_L005_R1_001.fastq.gz
	- P30612_116_S347_L005_R2_001.fastq.gz
	- P30612_117_S348_L005_R1_001.fastq.gz
	- P30612_117_S348_L005_R2_001.fastq.gz
	- P30612_118_S349_L005_R1_001.fastq.gz
	- P30612_118_S349_L005_R2_001.fastq.gz
 
*Koljö Fjord Samples:*

	- P30612_101_S332_L005_R1_001.fastq.gz
	- P30612_101_S332_L005_R2_001.fastq.gz
	- P30612_102_S333_L005_R1_001.fastq.gz
	- P30612_102_S333_L005_R2_001.fastq.gz
	- P30612_103_S334_L005_R1_001.fastq.gz
	- P30612_103_S334_L005_R2_001.fastq.gz
	- P30612_104_S335_L005_R1_001.fastq.gz
	- P30612_104_S335_L005_R2_001.fastq.gz
	- P30612_105_S336_L005_R1_001.fastq.gz
	- P30612_105_S336_L005_R2_001.fastq.gz
	- P30612_106_S337_L005_R1_001.fastq.gz
	- P30612_106_S337_L005_R2_001.fastq.gz
	- P30612_107_S338_L005_R1_001.fastq.gz
	- P30612_107_S338_L005_R2_001.fastq.gz
	- P30612_108_S339_L005_R1_001.fastq.gz
	- P30612_108_S339_L005_R2_001.fastq.gz
	- P30612_109_S340_L005_R1_001.fastq.gz
	- P30612_109_S340_L005_R2_001.fastq.gz
	- P30612_110_S341_L005_R1_001.fastq.gz
	- P30612_110_S341_L005_R2_001.fastq.gz
	- P30612_111_S342_L005_R1_001.fastq.gz
	- P30612_111_S342_L005_R2_001.fastq.gz
	- P30612_112_S343_L005_R1_001.fastq.gz
	- P30612_112_S343_L005_R2_001.fastq.gz
	- P30612_113_S344_L005_R1_001.fastq.gz
	- P30612_113_S344_L005_R2_001.fastq.gz
	- P30612_114_S345_L005_R1_001.fastq.gz
	- P30612_114_S345_L005_R2_001.fastq.gz
	- P30612_115_S346_L005_R1_001.fastq.gz
	- P30612_115_S346_L005_R2_001.fastq.gz
	- P30612_116_S347_L005_R1_001.fastq.gz
	- P30612_116_S347_L005_R2_001.fastq.gz
	- P30612_117_S348_L005_R1_001.fastq.gz
	- P30612_117_S348_L005_R2_001.fastq.gz
	- P30612_118_S349_L005_R1_001.fastq.gz
	- P30612_118_S349_L005_R2_001.fastq.gz

### 1. Preprocessing and trimming 

#### 1.1 Check reads quality report using fastQC program: FastQC V 0.11.9 (https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
        > mkdir fastQC_OUT
        > fastqc *_001.fastq.gz -t 15
#### 1.2 Viewing all results using MultiQC V 1.12 (https://github.com/MultiQC/MultiQC)
        > multiqc .

#### 1.3 Trimming and removing adapters: Illumina universal adapters: CutAdpat v4.5 (https://cutadapt.readthedocs.io/en/stable/) and Trimmomatic (http://www.usadellab.org/cms/?page=trimmomatic)
- Cutadapt v4.5
  
          > for file in *_L005_R1_001.fastq.gz; do
          # Get the base name of the file without the _R1.fastq suffix
          base=${file%_L005_R1_001.fastq.gz}

        # Run cutadapt on the paired end files and save the output files with the trimmed suffix
          cutadapt -a AGATCGGAAGAGCACACGTCTGAACTCCAGTCA -A AGATCGGAAGAGCGTCGTGTAGGGAAAGAGTGT --cores 30 --poly-a -o ${base}_trimmed_L005_R1_001.fastq.gz -p ${base}_trimmed_L005_R2_001.fastq.gz ${base}_L005_R1_001.fastq.gz ${base}_L005_R2_001.fastq.gz

          done
 
 - Trimmomatic v0.39
   
           > for f in *_trimmed_L005_R1_001.fastq.gz; do
             r1=$f; r2=${f/_trimmed_L005_R1_001.fastq.gz/_trimmed_L005_R2_001.fastq.gz}

             trimmomatic PE -threads 80 -phred33 $r1 $r2 ${r1/_trimmed_L005_R1_001.fastq.gz/_trimmed_R1.PwU.qtrim.fastq.gz} ${r1/_trimmed_L005_R1_001.fastq.gz/_trimmed_R1.unpaired.qtrim.fastq.gz} ${r2/_trimmed_L005_R2_001.fastq.gz/_trimmed_R2.PwU.qtrim.fastq.gz} ${r2/_trimmed_L005_R2_001.fastq.gz/_trimmed_R2.unpaired.qtrim.fastq.gz} LEADING:20 TRAILING:20 MINLEN:80 ILLUMINACLIP:/proj/naiss2023-23-559/nobackup/trimmomatic_adapters/NexteraPE-PE.fa:2:30:7
             done

**Check the trimmed libraries with FastQCQ and MultiQC**

### 2. Merging trimmed reads using FLASH V 1.2.11 

**taking the trimmed files as input (patter "_trimmed_R1.PwU.qtrim.fastq.g")**

	  > for f in *_trimmed_R1.PwU.qtrim.fastq.gz; do r1=$f; r2=${f/_trimmed_R1.PwU.qtrim.fastq.gz/_trimmed_R2.PwU.qtrim.fastq.gz}
	    flash -t 60 -m 4 -M 300 --allow-outies $r1 $r2 -o FLASH/${f/_trimmed_L005_R1_001.fastq.gz/merged};
            done

*Results:*
	RESULTS:
		[FLASH]     Percent combined: 44.92%
		[FLASH]     Percent combined: 45.16%
		[FLASH]     Percent combined: 48.80%
		[FLASH]     Percent combined: 49.98%
		[FLASH]     Percent combined: 46.30%
		[FLASH]     Percent combined: 47.59%
		[FLASH]     Percent combined: 51.16%
		[FLASH]     Percent combined: 47.28%
		[FLASH]     Percent combined: 42.00%
		[FLASH]     Percent combined: 49.53%
		[FLASH]     Percent combined: 55.20%
		[FLASH]     Percent combined: 63.08%
		[FLASH]     Percent combined: 49.70%
		[FLASH]     Percent combined: 49.84%
		[FLASH]     Percent combined: 49.23%
		[FLASH]     Percent combined: 53.91%
		[FLASH]     Percent combined: 42.71%
		[FLASH]     Percent combined: 48.94%
		[FLASH]     Percent combined: 71.26%
		[FLASH]     Percent combined: 57.87%
		[FLASH]     Percent combined: 62.02%
		[FLASH]     Percent combined: 53.83%
		[FLASH]     Percent combined: 68.32%
		[FLASH]     Percent combined: 54.73%
		[FLASH]     Percent combined: 51.57%
		[FLASH]     Percent combined: 58.96%
		[FLASH]     Percent combined: 50.74%
		[FLASH]     Percent combined: 54.48%
		[FLASH]     Percent combined: 50.71%
		[FLASH]     Percent combined: 52.03%
		[FLASH]     Percent combined: 70.62%
		[FLASH]     Percent combined: 56.69%
		[FLASH]     Percent combined: 68.77%
		[FLASH]     Percent combined: 42.19%
		[FLASH]     Percent combined: 59.51%
		[FLASH]     Percent combined: 73.29%

The merged and unmerged sequences are used separately to avoid data waste. So, we are including all sequences.

Run SortmeRNA separately: using the merged files as a single file and in paired-end mode the unassembled files, and then concatenating both results for each sample.

### 3. Taxonomic classification by rRNA

#### 3.2. Dividing the FLASH output files in two folders:  ExtendedFrags and No_combined. 

    The assembled files were placed into the ExtendedFrags folder
    
    
        P30612_102_S333_trimmed_R1.PwU.qtrim.fastq.gz.extendedFrags.fastq
        P30612_103_S334_trimmed_R1.PwU.qtrim.fastq.gz.extendedFrags.fastq
        ...
        
   **To speed up the next SortmeRNA process I splitted these files:**
   
   
##########   Code  ##############
    
    #!/bin/bash -l

    #SBATCH -A naiss2024-22-947
    #SBATCH -p shared
    #SBATCH -n 20
    #SBATCH -t 06:00:00
    #SBATCH -J pigz_Kristineberg

    module load bioinfo-tools
    module load pigz/2.8

    ##### Split files and compress outputs

    # Input directory containing fastq files
    input_dir="."

    # Output directory for compressed files
    output_dir="compressed_files"

    # Create the output directory if it doesn't exist
    mkdir -p "$output_dir"

    # Loop through each fastq file in the input directory
    for input_file in "$input_dir"/*_trimmed_R1.PwU.qtrim.fastq.gz.extendedFrags.fastq; do
        # Extract the sample name from the input file (e.g., P29881_101)
        sample_name=$(basename "$input_file" | cut -d'_' -f1-2)

        # Split the input file into smaller files with a custom suffix length to ensure unique names
        split -l 100000000 -d --additional-suffix=.fastq "$input_file" "${sample_name}_split_"

        # Compress the split files using pigz
        for split_file in "${sample_name}_split_"*.fastq; do
            pigz -p 20 "$split_file"
        done

        # Move the compressed files to the output directory
        mv "${sample_name}_split_"*.gz "$output_dir"
    done

    echo "Fastq files split, compressed, and moved to the output directory."
######################################################################################
    
**The folder "No_combined" contains:**

                    P30612_101_S332_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_1.fastq
                    P30612_101_S332_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_2.fastq
                    P30612_102_S333_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_1.fastq
                    P30612_102_S333_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_2.fastq
		    ...
    
**This will not be splitted and used as imput directly to SortmeRNA**

#### 3.1. rRNA (SSU rRNA) reads extraction with SortMeRNA 4.3.6

 - SILVA database (silva-bac-16s-id90.fasta; Kopylova et al., 2012) as reference.

   #!/bin/bash -l

#SBATCH -A naiss2023-22-1280
#SBATCH -p node
#SBATCH -n 1
#SBATCH -t 03-00:00:00
#SBATCH -J sortKritine

module load bioinfo-tools
module load SortMeRNA/4.3.4

for f in *fastq.gz; do
        r1=$f;

        sortmerna --ref $SORTMERNA_DBS/rRNA_databases/silva-bac-16s-id90.fasta --reads $r1 --fastx -threads 16 --workdir ${r1/fastq.gz/sortmerna_workdir_16SrRNA}/ --align
    ed ${r1/fastq.gz/aligned_16S_rRNA}
done

   	
#### 3.2. Determine taxonomic composition

 - Programs: Kraken2 and Bracken.
 - Using SILVA 138 SSU (June 2024) database as reference.

module load bioinfo-tools
module load Kraken2/2.1.2-20211210-4f648f5

for file in *_rRNA_FINAL.fasta.gz; do

kraken2 --db /home/alfon/Kraken2/Silva_138_SSU_Jun32024 --threads 15 --confidence 0.0 -use-names --gzip-compressed --report-zero-counts --output $file"_Kraken_db-Silva_16S" --report $file"_kraken2_Silva16S_report.txt" $file; done

**bracken**

module load bioinfo-tools
module load Kraken2/2.1.2-20211210-4f648f5

for r in *_report.txt; do /proj/naiss2023-23-559/nobackup/alexis/Bracken/bracken -d /home/alfon/Kraken2/Silva_138_SSU_Jun32024 -i $r -o ${r/_report.txt/_bracken_OUT.txt} -r 200 -
l G -t 15; done


#### 3.3 Further analysis: Cable bacteria determination by assembly of rRNA sequences

Cable bacteria abundance was further analysed in Koljö Fjord, assembling the rRNA gene reads (obtained by SortMeRNA ) using rnaSPAdes (spades V 4.0.0) with “-k 31,55,77,97,127.” 16S rRNA gene sequences were identified with Barrnap V0.9 and aligned against the SILVA_138.1_SSURef_NR99 database, using 44 Ca. Electrothrix spp. 16S rRNA gene sequences, using BLASTN V2.15.0+ with “-max_target_seqs 1.” 16S rRNA gene sequence matching with Ca. Electrothrix spp. with >90% identity, e-value < 1x10e-10 and query cover > 95% were selected and quantified using coverM with the mode “contig” and method “-m  tpm,” previous mapping of original rRNA gene reads against the assembled and annotated Ca. Electrothrix spp. 16S rRNA sequences. Thirteen partial 16S rRNA Ca. Electrothrix gene sequences ranging from 411 bp to 941 base pairs (bp) were obtained.

- Assembly rRNA sequences (all the rRNA files from SortMeRNA concatenated in the file P30612_129_16S_rRNA_FINAL.fasta.gz)
  
  		> rnaspades.py -s P30612_129_16S_rRNA_FINAL.fasta.gz -o spades_129_20-22_16S --meta --threads 16


### 4. Obtaining the non-rRNA sequences (mRNA) with SortMeRNA

Using the smr_v4.3_default_db.fasta file as reference. The following is the mode to paired-end libraies ( Paired-end mode - notCombined reads). To the combined (to merged libraries the mode was single-end)

    #!/bin/bash -l

    #SBATCH -A naiss2024-22-947
    #SBATCH -p shared
    #SBATCH -n 50
    #SBATCH -t 20:00:00
    #SBATCH -J sortmerna_Krist2

    module load bioinfo-tools
    module load SortMeRNA/4.3.4

    for f in *_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_1.fastq; do
        r1=$f; r2=${f/_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_1.fastq/_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_2.fastq}

        sortmerna --ref  $SORTMERNA_DBS/rRNA_databases/smr_v4.3_default_db.fasta --idx-dir $SORTMERNA_DBS/index/ --reads $r1 --reads $r2 --fastx --out2 --paired_out -threads 50 --workdir ${r1/_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_1.fastq/sortmerna_workdir_Non_rRNA}/ --other ${r1/_trimmed_R1.PwU.qtrim.fastq.gz.notCombined_1.fastq/other_non-rRNA}

    done


