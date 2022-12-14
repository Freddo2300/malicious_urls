# malicious_urls
Exam project for Cybersecurity Foundations and Analytics (W/22)

**caution** malicious_phish.csv file contains malicious urls, so be careful not to open any urls in the browser

## getting started

clone this project:
```console
git clone https://github.com/Freddo2300/malicious_urls
```
create a virtual environment (**skip if you already have one**)

**Linux and Mac**:
```console
python3 -m venv venv
source venv/bin/activate
```

**Windows**:
```console
python -m venv venv
source venv/Scripts/activate.bat
```

install required dependencies into virtual environment:
```console
pip install -r requirements.txt
```
## Attribution
This project has taken a lot of inspiration from the works of other people:

The dataset is a synthesis of multiple datasets and published by Manu Siddhartha 

https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset

Throughout the code, particular pieces are inspired by:

https://www.kaggle.com/code/jingyanshang/url-s-feature-analysis/notebook

https://www.kaggle.com/code/hamzamanssor/detection-malicious-url-using-ml-models/notebook

https://www.kaggle.com/code/arjanso/reducing-dataframe-memory-size-by-65/notebook
