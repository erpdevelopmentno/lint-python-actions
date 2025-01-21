# Create workflow with lint-python-actions
- create the folder .github/workflows and add the .yaml file
- consistency code errors can be fixed in VS Code using the following commands:

## Install Black

```
python -m pip install black
```

## Install isort

```
python -m pip install isort
```

## Run isort check on all files
```
isort --check .
black --check .
```

## Eventually fix file automatically
fix files
```
isort .\filename.py
black .  # for all files
```
