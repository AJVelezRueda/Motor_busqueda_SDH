## Installation

### OS Dependencies

```bash
sudo apt install ffmpeg
```

### Python Dependencies

```bash
$ python -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```


### Running the project in jupyter

```bash
jupyter nbextension enable --py widgetsnbextension
jupyter notebook

# or with lab
jupyter labextension enable  widgetsnbextension
jupyter lab
```