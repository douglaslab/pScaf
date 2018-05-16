# pScaf Supplementary Files

## 1. SnapGene files

Empty vector (pScaf.dna) and vectors with inserts to create designated scaffolds. For example, `pScaf-3024.1.dna` can be used to generate a scaffold of length `3024` bases.

## 2. Scaffold sequences

The txt files contain the scaffold sequences used in our manuscript DNA origami designs.

The files are named `pScaf-[insert length].[variant].txt`, where the insert length is the full length of the scaffold, and the variant is some unique identifier.

Here, all scaffolds are named variant `1`, and future pScaf-derived scaffolds of the similar length can be named sequentially.

The common fixed region of the scaffolds is 393 bases long:

```
GGATCCACGCGCCCTGTAGCGGCGCATTAAGCGCGGCGGGTGTGGTGGTTACGCGCAGCGTGACCGCTACACTTGCCAGC
GCCCTAGCGCCCGCTCCTTTCGCTTTCTTCCCTTCCTTTCTCGCCACGTTCGCCGGCTTTCCCCGTCAAGCTCTAAATCG
GGGGCTCCCTTTAGGGTTCCGATTTAGTGCTTTACGGCACCTCGACCCCAAAAAACTTGATTTGGGTGATGGTTCACGTA
GTGGGCCATCGCCCTGATAGACGGTTTTTCGCCCTTTGACGTTGGAGTCCACGTTCTTTAATAGTGGACTCTTGTTCCAA
ACTGGAACAACACTCAACCCTATCTCGGGCTATTCTTTTGATTTATAAGGGATTTTGCCGATTTCGGGGTACC
```

The scaffold sequences have been adjusted so the fixed region is at the beginning.

For those who wish to reproduce the staple sequences in our manuscript, we have provided alternate versions of each scaffold sequence in the `permuted` subfolder. This is because we originally exported our staples using sequences that were permuted by `299` bases, such that the first bases applied at the 5' scaffold breakpoint were `AATAGTGGACTC...`.

## 3. Cadnano designs

The Cadnano design source files are provided in legacy json format. All files can be opened with Cadnano [v0.2.3](http://cadnano.org/legacy) or later.

## 4. Staple sequences

Exported staple sequences. The CSV files are exported from Cadnano. The XLS files are manually processed in preparation for ordering.

The six-helix-bundle (6hb) trimer connectors were designed by hand, and provided in `6hb-timer-connectors.xlsx`.