# HH2 Manuscript scripts and tools

This is a collection of custom scripts and analysis tools used in the HH2 discovery manuscript.

## vcfFileConcordanceAnalysis.py

```bash
usage: vcfFileConcordanceAnalysis.py [-h] -v VCF -o OUTPUT -c CHROMOSOME -s
                                     START -e END -l LIST [-m MIN]

Carrier concordance analysis from gzipped vcf files

optional arguments:
  -h, --help            show this help message and exit
  -v VCF, --vcf VCF     Input gzipped vcf file. Required
  -o OUTPUT, --output OUTPUT
                        Output file basename. Output files are (basename).tab
                        and (basename).pdf
  -c CHROMOSOME, --chromosome CHROMOSOME
                        Chromosome for filtering coordinates
  -s START, --start START
                        Start base for filtering coordinates
  -e END, --end END     End base for filtering coordinates
  -l LIST, --list LIST  Newline delimited list of carrier animals. Carriers
                        are assumed to be heterozygotes and all others
                        homozygous reference
  -m MIN, --min MIN     Minimum y value to plot (float)

```