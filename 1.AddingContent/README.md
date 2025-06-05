![](images/smiley.png) 

<img width="20%" src="images/smiley.png">



#
Create code like this

```
Block of code
```

`these words` printed in  monospace

[Genomics Aotearoa]([text](https://www.genomics-aotearoa.org.nz/))


### Overview
in this section  we willl..

### Learning Objectives
1. how to one
2. how to two

Script:

```
/bin/sh

# Create directory in which to perform analysis, and change to that directory
mkdir YeastAnalysis
cd YeastAnalysis

# Create subdirectories to hold data and output from FASTQC
mkdir fastq
mkdir fastqc_output

# Change to data directory, and download data from FigShare
cd fastq
wget -O yeast.fastq https://ndownloader.figshare.com/files/4790242

# Run fastqc command on the file yeast.fastq and save the output in fastqc_output
fastqc -o ../fastqc_output yeast.fastq
```

*Adding commentary...*

# Example header
## sub header
### sub sub header
#### sub sub sub header

```{r}
# This is a comment inside an R code chunk
summary(cars)  # Summarize the cars dataset
```

```markdown
<!-- This is a comment in the Markdown text -->

