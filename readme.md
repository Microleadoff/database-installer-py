# Introduction

This is a python script made to initialize databases for practicing SQL.

## Installation

- Make sure you have at least Python V3.8 installed on your computer.
- Unzip all databases in the databases folder. Make sure all files have the same name as the zip files, but with the .sql extension.
- install mysql.connector : ```pip install mysql-connector-python``` or ```py -m pip install mysql-connector-python```

## Execution

```bash
# Windows
py main.py

# Mac / Linux
python3 main.py
```

## Known issues

- using latest python version (3.12) make database commit not working by now (cause mysql.connector not updated yet). So downgrade to 3.8 or 3.10 to make it work again !
