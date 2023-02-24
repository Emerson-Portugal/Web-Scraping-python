# Como crear un Web Scraping con Python

## Requistos
> Debes tener instalado Python 

> Vas a instalar las librerias para poder ejecuar el scraping

```
pip install -r ".\requirements.txt"
```

## Explicacion del codigo

> Se vas importar las librerias <b>requests</b> y <b>BeautifulSoup</b>

> Se guarda en la una variable la url del sitio web que se le hara el Scraping

> Por ultimo, se hara convercion, para que python pueda extraer la informacion que le solicitemos 

```
import requests
from bs4 import BeautifulSoup

url = requests.get('https://www.example)
soup = BeautifulSoup(url.content, 'html.parser')
```

## Ejecucion

```
python nombre_archivo.py
```

## Opcional 

Si queremos crear un entorno virtual con python, para no tener problemas con las librerias y tener un monton de librerias instalas en tu PC, te recomiendo un entorno virtual


>creamos el entorno virtual
```
python -m virtualenv venv
```

> Ejecutamos virtualenv
```python
.\venv\Scripts\activate
```

> Detemos virtualenv
```python
deactivate
```