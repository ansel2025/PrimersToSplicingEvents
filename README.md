# PrimersToSplicingEvents
Find out the splicing events with given pair of primers

Usage

```
>java -Xmx10g -jar PrimersToSplicingEvents.jar ../TranscriptE
xtraction/Homo_sapiens.GRCh38.82.dna.primary_assembly.fa.gz MISO.GRCh38.82.gff3
GTCGGAGGACGCGAACCGGCACG CCATCCTGCTCTTTCAGGCT

>SE     3:58237532:58237916:+@3:58249878:58249942:+@3:58256562:58256705:+.B
+3:58237746-58256590(200)
GTCGGAGGACGCGAACCGGCACGCTGCGCCTTTAAGGAGTCCAGCTGGGCTGGGCGCCGGAGCTGGGAGCGGCGCGGGTA
GGAGCCCGGCGGCAGGTCCCAGCCCGGGGCTAGAGACCGAGGGCCGGGGTCCGGGCCCGGCGGCGGGACCCAGGCGGTTG
AGGCTGGTCAGGAGTCAGCCAGCCTGAAAGAGCAGGATGG
>SE     3:58237532:58237916:+@3:58249878:58249942:+@3:58256562:58256705:+.A
+3:58237746-58256590(265)
GTCGGAGGACGCGAACCGGCACGCTGCGCCTTTAAGGAGTCCAGCTGGGCTGGGCGCCGGAGCTGGGAGCGGCGCGGGTA
GGAGCCCGGCGGCAGGTCCCAGCCCGGGGCTAGAGACCGAGGGCCGGGGTCCGGGCCCGGCGGCGGGACCCAGGCGGTTG
AGGCTGGTCAGAATCTCATTTTCAGCTTCTGCCAGAGCCAGTAGCAGTTGGGAAAGAAGGCTGTGCTCTTTGAAGAGAGT
CAGCCAGCCTGAAAGAGCAGGATGG
```

