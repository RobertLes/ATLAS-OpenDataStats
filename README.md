```
git clone git@github.com:RobertLes/ATLAS-OpenDataStats.git
cd ATLAS-OpenDataStats
```


Need pyhton 3.11>
```
python3 -m venv ~/venv/open-data
source ~/venv/open-data/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=OpenDataStatsTutorial
```

```
conda create --name open-data python=3.10 --file requirements.txt
conda activate open-data
python -m ipykernel install --user --name=OpenDataStatsTutorial
```

```
jupyter notebook HyyAnalysis.ipynb &
```


```
jupyter kernelspec uninstall opendatastatstutorial
```

```
rm -r ~/venv/open-data
pip cache purge
```

Or similarly for conda:
```
conda env remove --name open-data
conda clean --all
```
