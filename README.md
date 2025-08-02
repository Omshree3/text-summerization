# TextSummerizerEndToEnd
An End to End text summarize project


## Workflows
Update the followings
1.  config/config.yaml
2.  params.yaml
3.  src/TextSummarizer/entity
4.  configuration manager in src/TextSummarizer/config
5.  src/TextSummarizer/components
6.  src/TextSummarizer/pipeline
7.  main.py
8.   app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/durgeshmca/TextSummerizerEndToEnd
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create --prefix ./env summary python=3.11 -y
```

```bash
conda activate ./env
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bashSS
# Finally run the following command
python app.py
```