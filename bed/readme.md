# Custom tracks format for UCSC

## Dummy data

1. Go to https://genome.ucsc.edu/cgi-bin/hgCustom

2. Make sure the genome assembly is `Current Genome: May 2017 (GRCz11/danRer11)`

3. Paste the following as data source:

```
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/intervals-1.bed
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/loops.arcs
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/intervals-2.bed
```

4. Submit, and enjoy :-). These tracks contain two loci.

Go to Browser positions

`chr5:13,389,472-13,479,561`

`chr17:32,150,000-32,291,000`


Double click on a track to show all features


## Formatted data

1. Go to https://genome.ucsc.edu/cgi-bin/hgCustom


2. Make sure the genome assembly is `Current Genome: May 2017 (GRCz11/danRer11)`



3. Paste the following as data source:


```
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/LEC-TADs-PanaraArnoldGloger2026-tst.bed
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/BEC-TADs-PanaraArnoldGloger2026-tst.bed
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/OCR-PanaraArnoldGloger2026-tst.bed
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/Loops-LEC-PanaraArnoldGloger2026-tst.arcs
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/Loops-common-PanaraArnoldGloger2026-tst.arcs
```

Visibility of the tracks can be altered by clicking on the track. This is especially useful for TAD tracks.

To include differential boundaries, add:

```
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/LEC-difbnds-difTADs-PanaraArnoldGloger2026-tst.bed
https://raw.githubusercontent.com/agata-sm/plac-zabaw/refs/heads/main/bed/BEC-difbnds-difTADs-PanaraArnoldGloger2026-tst.bed
```

These tracks contain one locus.

