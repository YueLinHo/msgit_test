This is a dummy repository that testing the .gitattributes and the Normalization.

The branch ```not_normalize``` just commits the .gitattributes without doing the normalization.
When you clone this repo and checkout that branch for several times, you will get some cloned repositoies with some files modified.
(Using ```git status | wc -l``` to check it, or using TortoiseGit's Show Log afeter clone finished.)

The branch ```normalize``` fix it by doing the normalization.
