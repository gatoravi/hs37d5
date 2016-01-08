# hs37d5
Testing "git lfs"

##Example
Testing this out on a couple of 'gtf' files - one of them is '256 MB'
The github limit for files currently is 100MB
The 'git lfs' limit  on github is 2GB
```
git lfs track *gtf
git add *
git commit -m "Add Ensembl annotations"
vim genes_chr22.gtf
git add -p
git commit -m "Remove last few lines"
git push origin master
git revert 6f55a6297f71b9b427f3b53428f60f6bee9f6597
git push origin master
```
