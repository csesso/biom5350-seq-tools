# biom5350-seq-tools

# <span style='font-size:small'><span style='font-family:Arial'>In-class repository for calculating the GC content, AT content, and length of various sequences.</span></span>

## Usage

```
$> python gc_content.py example.fasta
```

Expected output is the name of each sequence followed by %GC, %AT, and length; then, a calculation of the average GC content across all sequences. For example:

```
seq1_AT_rich    GC = 0.0%,      AT = 100.0%,    length = 83nt
seq2_balanced   GC = 48.8%,     AT = 51.2%,     length = 80nt
seq3_GC_rich    GC = 100.0%,    AT = 0.0%,      length = 79nt
seq4_with_N     GC = 50.0%,     AT = 50.0%,     length = 50nt
The average GC content of all sequences is 49.6875%
```

## Credits

Claudia Sesso

BIOM5350

