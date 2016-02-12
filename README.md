# Datasets
Dataset repo managed by Git LFS (Large File Storage)

## Operating Git LFS
Refer [here](https://git-lfs.github.com/) for installation

## MongoDB
Make sure that:

1. you have the `dump` directory, which contains binary exports of the Mongo database

2. you have `mongod` running in a shell


Then, we are going to use `mongorestore` which converts the binary files in `dump` into a proper MongoDB instance:

`mongorestore <path-to>/dump`
