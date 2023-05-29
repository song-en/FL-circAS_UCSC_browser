# FL-circAS track hub for UCSC Genome Browser

## Directory Tree
```
FL-circAS_hub
├── README.md
├── genomes.txt
├── hg38
│   ├── FL-circAS_isoforms.hg38.bb
│   └── trackDb.txt
├── hub.txt
└── mm10
    ├── FL-circAS_isoforms.mm10.bb
    └── trackDb.txt
```

## Usage and Examples

For hg38:
```
http://genome.ucsc.edu/cgi-bin/hgTracks?
hubUrl=https://raw.githubusercontent.com/song-en/FL-circAS_UCSC_browser/main/hub.txt
&
db=hg38
&
position=chr1:100038200-100073852
&
hideTracks=1
&
knownGene=pack
&
knownGene_imgOrd=1
&
isoform_track_hg38=full
&
isoform_track_hg38_imgOrd=2
&
pix=1450
&
hgt.labelWidth=40
```

For mm10:
```
http://genome.ucsc.edu/cgi-bin/hgTracks?
hubUrl=https://raw.githubusercontent.com/song-en/FL-circAS_UCSC_browser/main/hub.txt
&
db=mm10
&
position=chr1:66772406-66802668
&
hideTracks=1
&
knownGene=pack
&
knownGene_imgOrd=1
&
isoform_track_mm10=full
&
isoform_track_mm10_imgOrd=2
&
pix=1450
&
hgt.labelWidth=40
```

## References

- https://genome-asia.ucsc.edu/goldenPath/help/hgTrackHubHelp#Setup
- https://genome.ucsc.edu/goldenPath/help/customTrack.html
- http://genome.ucsc.edu/goldenPath/help/hubQuickStartFilter.html
