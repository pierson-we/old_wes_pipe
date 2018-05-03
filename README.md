# wes_pipe
WES analysis pipeline

WES Analysis pipeline

fastq file
	QC fastq file (FastQC)
		Align reads (Bowtie2)
			Variant Calling
				SNVs
				CNVs
					Having normal samples will help correct for Exome capture biases
				InDels
				Inversions
				Translocations
