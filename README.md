# My notes on using linux

## Working with PDFs

### Change pdf page size

```
pdfjam --outfile  out.pdf --paper a4paper in.pdf
```

### Create pdf from images

```
convert file1.jpg file.png *.pdf out.pdf
```

### Show information about pdf file

```
pdfinfo file.pdf
```

output sample:

```
Title:          2K:@>9:0
Producer:       https://imagemagick.org
CreationDate:   Sat Dec 28 13:22:05 2019 MSK
ModDate:        Sat Dec 28 13:22:05 2019 MSK
Tagged:         no
UserProperties: no
Suspects:       no
Form:           none
JavaScript:     no
Pages:          2
Encrypted:      no
Page size:      380 x 537 pts
Page rot:       0
File size:      194368 bytes
Optimized:      no
PDF version:    1.7
```
