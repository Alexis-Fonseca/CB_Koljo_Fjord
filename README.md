# CB_Koljö_Fjord
This repository describes the main scripts and the procedure followed to analyze the metatranscriptomic data of the manuscript: "**Unexpected Abundance of Cable Bacteria in Deep Anoxic Sediments Reveals a New Biogeochemical Niche**."

The objective of the data analysis was to investigate the presence of sulfide-oxidizing bacteria, specifically the so-called cable bacteria (marine genus _Candidatus_ Electrothrix), in the Kristineberg Bay and Koljö Fjord areas on the west coast of Sweden. Sampling was conducted in 2023, resulting in the collection of 36 samples. Six sediment layers at varying depths were sampled in triplicate at each location. A total of 18 sediment samples per site (36 in total) were subjected to RNA extraction and sequencing using a NovaSeqXPlus platform (NovaSeqXSeries Control Software 1.2.0.28691) configured for 2 × 150 bp. The vertical sediment profiles included 0-1, 1-3, 7-9, 9-11, 20-22, and 30-32 cm depths. Additionally, data from two locations in the Tvärminne Archipelago, situated in Southern Finland, designated as Offshore and Nearshore (Hermans et al., 2024), were used to compare places.
The raw data is availabe at: https://www.ncbi.nlm.nih.gov/bioproject/?term=(PRJNA1253322)%20AND%20bioproject_sra[filter]%20NOT%20bioproject_gap[filter]

## The data analysis was broken down as follows:

**Samples:**

*Kristineberg Bay samples:*

-P30612_101_S332_L005_R1_001.fastq.gz
-P30612_101_S332_L005_R2_001.fastq.gz
-P30612_102_S333_L005_R1_001.fastq.gz
-P30612_102_S333_L005_R2_001.fastq.gz
-P30612_103_S334_L005_R1_001.fastq.gz
-P30612_103_S334_L005_R2_001.fastq.gz
-P30612_104_S335_L005_R1_001.fastq.gz
-P30612_104_S335_L005_R2_001.fastq.gz
-P30612_105_S336_L005_R1_001.fastq.gz
-P30612_105_S336_L005_R2_001.fastq.gz
-P30612_106_S337_L005_R1_001.fastq.gz
-P30612_106_S337_L005_R2_001.fastq.gz
-P30612_107_S338_L005_R1_001.fastq.gz
-P30612_107_S338_L005_R2_001.fastq.gz
-P30612_108_S339_L005_R1_001.fastq.gz
-P30612_108_S339_L005_R2_001.fastq.gz
-P30612_109_S340_L005_R1_001.fastq.gz
-P30612_109_S340_L005_R2_001.fastq.gz
-P30612_110_S341_L005_R1_001.fastq.gz
-P30612_110_S341_L005_R2_001.fastq.gz
-P30612_111_S342_L005_R1_001.fastq.gz
-P30612_111_S342_L005_R2_001.fastq.gz
-P30612_112_S343_L005_R1_001.fastq.gz
-P30612_112_S343_L005_R2_001.fastq.gz
-P30612_113_S344_L005_R1_001.fastq.gz
-P30612_113_S344_L005_R2_001.fastq.gz
-P30612_114_S345_L005_R1_001.fastq.gz
-P30612_114_S345_L005_R2_001.fastq.gz
-P30612_115_S346_L005_R1_001.fastq.gz
-P30612_115_S346_L005_R2_001.fastq.gz
-P30612_116_S347_L005_R1_001.fastq.gz
-P30612_116_S347_L005_R2_001.fastq.gz
-P30612_117_S348_L005_R1_001.fastq.gz
-P30612_117_S348_L005_R2_001.fastq.gz
-P30612_118_S349_L005_R1_001.fastq.gz
-P30612_118_S349_L005_R2_001.fastq.gz

*Koljö Fjord Samples:*

-P30612_119_S350_L005_R1_001.fastq.gz
-P30612_119_S350_L005_R2_001.fastq.gz
-P30612_120_S351_L005_R1_001.fastq.gz
-P30612_120_S351_L005_R2_001.fastq.gz
-P30612_121_S352_L005_R1_001.fastq.gz
-P30612_121_S352_L005_R2_001.fastq.gz
-P30612_122_S353_L005_R1_001.fastq.gz
-P30612_122_S353_L005_R2_001.fastq.gz
-P30612_123_S354_L005_R1_001.fastq.gz
-P30612_123_S354_L005_R2_001.fastq.gz
-P30612_124_S355_L005_R1_001.fastq.gz
-P30612_124_S355_L005_R2_001.fastq.gz
-P30612_125_S356_L005_R1_001.fastq.gz
-P30612_125_S356_L005_R2_001.fastq.gz
-P30612_126_S357_L005_R1_001.fastq.gz
-P30612_126_S357_L005_R2_001.fastq.gz
-P30612_127_S358_L005_R1_001.fastq.gz
-P30612_127_S358_L005_R2_001.fastq.gz
-P30612_128_S359_L005_R1_001.fastq.gz
-P30612_128_S359_L005_R2_001.fastq.gz
-P30612_129_S360_L005_R1_001.fastq.gz
-P30612_129_S360_L005_R2_001.fastq.gz
-P30612_130_S361_L005_R1_001.fastq.gz
-P30612_130_S361_L005_R2_001.fastq.gz
-P30612_131_S362_L005_R1_001.fastq.gz
-P30612_131_S362_L005_R2_001.fastq.gz
-P30612_132_S363_L005_R1_001.fastq.gz
-P30612_132_S363_L005_R2_001.fastq.gz
-P30612_133_S364_L005_R1_001.fastq.gz
-P30612_133_S364_L005_R2_001.fastq.gz
-P30612_134_S365_L005_R1_001.fastq.gz
-P30612_134_S365_L005_R2_001.fastq.gz
-P30612_135_S366_L005_R1_001.fastq.gz
-P30612_135_S366_L005_R2_001.fastq.gz
-P30612_136_S367_L005_R1_001.fastq.gz
-P30612_136_S367_L005_R2_001.fastq.gz

### 1. Preprocessing and trimming 

### 2. 

