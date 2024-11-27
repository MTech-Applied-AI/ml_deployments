
### Installing Miniconda



[Reference Miniconda Website](https://docs.anaconda.com/miniconda/install/#quick-command-line-install)

```
mkdir -p ~/miniconda3

curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh

bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3

rm ~/miniconda3/miniconda.sh

```


#### After installing, close and reopen your terminal application or refresh it by running the following command:

```
source ~/miniconda3/bin/activate
```

#### To initialize conda on all available shells, run the following command:


```
conda init --all
```

#### Conda Frequently Used Commands

```

conda create -n mlops python=3.8

conda activate mlops

# info about all envs
conda info --envs

# for installing jupyter server on the conda env
pip install jupyter


```

#### For deactivating the conda env
```
    conda deactivate
```


