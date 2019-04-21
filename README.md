# ngsproject-bam-parser

In this project I used E.coli organism
Downloaded SRA from ncbi and refernce genome and GTF from ensemblbacteria

firstly I convert SRA file to fastq file and split R1 and R2
I have around 1M reads
SRX3759025: RNA-Seq of EsCas13d and RspCas13d crRNA in vitro
1 ILLUMINA (NextSeq 550) run: 250,000 spots, 37.2M bases, 15.3Mb downloads

Design: See STAR Methods: RNA sequencing
Submitted by: Arbor Biotechnologies
Study: CRISPR-Cas13d NGS data
PRJNA434567 • SRP133859 • All experiments • All runs
show Abstract
Sample: E. siraeum and R. sp Cas13d crRNA processing in vitro
SAMN08631469 • SRS3014034 • All experiments • All runs
Organism: Escherichia coli
Library:
Name: 7
Instrument: NextSeq 550
Strategy: WGS
Source: TRANSCRIPTOMIC
Selection: RT-PCR
Layout: PAIRED
Fastaq quality control for data showed that problem in 
Per base sequence content
Sequence Duplication Levels
Overrepresented sequences
Adapter Content
in R1 with this summary
Measure	Value
Filename	SRR6800317_1.fastq
File type	Conventional base calls
Encoding	Sanger / Illumina 1.9
Total Sequences	250000
Sequences flagged as poor quality	0
Sequence length	69-75
%GC	46
and in R2 with this summary
Measure	Value
Filename	SRR6800317_2.fastq
File type	Conventional base calls
Encoding	Sanger / Illumina 1.9
Total Sequences	250000
Sequences flagged as poor quality	0
Sequence length	69-75
%GC	45

Did trimming for data as mild trimming
Hisat Alignment
and Assembly
