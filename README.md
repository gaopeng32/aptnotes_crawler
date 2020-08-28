# Instructions for downloading APTnotes reports

Forked from: <https://github.com/aptnotes>

Reports summary: <https://github.com/aptnotes/data/blob/master/APTnotes.csv>

- Latest article: 11/05/2019

Commands (tested on 08/18/2020):

```sh
conda create -n aptnotes_download python=3.5
pip install -r APTnotes_async_requirements.txt
pip uninstall python-magic
pip install python-magic-bin==0.4.14
conda activate aptnotes_download
cd tools/
python APTnotes_async_download_python35.py
```

Reports will be downloaded in `tools/`.

Archive of reports downloaded: <https://drive.google.com/drive/folders/1paRBjSiS7XJlBkvDwEPJcSk2eDDxCZ0P?usp=sharing>