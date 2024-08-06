
Create Conda Environment with osx-64 Subdir
Open Terminal in Rosetta mode: To ensure that the Conda commands you run are executed under Rosetta 2, you should start Terminal in Rosetta mode. You can do this by duplicating the Terminal app in the Finder, getting info on the duplicate (right-click > Get Info), and checking the “Open using Rosetta” option.

Create a new Conda environment specifying the platform: Use the following command in the Terminal to create a new environment, specifying osx-64 for the platform. Replace myenv with the name you want to give to your environment, and adjust the Python version as necessary.
```
CONDA_SUBDIR=osx-64 conda create --name myenv python=2.7
```
```
conda activate myenv
```

```
https://medium.com/@maralzar1374/anacondas-bridge-running-python-2-7-on-m1-macs-with-rosetta-2-8ef2d83a9f06
```


lefse
```
https://forum.qiime2.org/t/lefse-after-qiime2-to-test-at-all-taxonomic-levels/15462/3
```
