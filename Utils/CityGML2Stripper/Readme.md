A small utility that strip a CityGML 2.0 (XML) 
file and serializes the result in a new CityGML (XML) 
file. It removes appearences and generic attributes.

## Installation
```bash
$ virtualenv -p python3 venv
$ . venv/bin/activate
(venv)$ pip install -r requirements.txt
```

## Usages
* With input files:
```bash
(venv)$ python CityGML2Stripper.py --input filename_1.gml --output output.gml
```
