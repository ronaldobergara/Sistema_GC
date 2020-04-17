# Sistema_GC
Sistema para gestão de conhecimento

## Como Desenvolver?
1. Clone o repositorio.
2. Crie um virtualenv com python 3.8.0
3. Ative o Virtualenv.
4. instale as dependencias.


```console
git clone https://github.com/ronaldobergara/Sistema_GC.git Sistema_GC
cd Sistema_GC
python -m venv .Sistema_GC
cd .Sistema_GC/Scripts/
activate
echo @python %VIRTUAL_ENV%\..\manage.py %* > manage.bat
cd..
cd..
pip install -r requirements.txt
```