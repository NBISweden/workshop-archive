# Workshop archive

This is a github pages portal for accessing old courses given by NBIS.
Public URL: [https://nbisweden.github.io/workshop-archive/](https://nbisweden.github.io/workshop-archive/)

## Archive a workshop

To add a workshop instance, add a git submodule as shown below:

```
git submodule add -b feb2023 -- https://github.com/NBISweden/workshop-scrnaseq.git  workshop-scRNAseq/2023-01-30
```

`-b`: a branch on the workshop repo that should be archived  
`-- https://github.com/NBISweden/workshop-scrnaseq.git`: URL to the workshop repo  
`workshop-scRNAseq/2023-01-30`: A path in the archive repo 

Check in **.gitmodules** that it has been added correctly  

`cat .gitmodules`

Update **index.md** with a link to the archive

`* [2023-01-30](workshop-scRNAseq/2023-01-30)`

Push changes
