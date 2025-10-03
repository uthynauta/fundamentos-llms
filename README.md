# Fundamentos sobre LLMs
Este es el repositorio oficial sobre el curso de Fundamentos sobre LLMs.

## Instalación de Python

Descargar e installar [Python 3.11](https://www.python.org/downloads/release/python-3119/) de la página oficial.

Abrir una terminal, ya sea en PowerShell o UNIX, y verificar que la version de Python sea 3.11.x.

En caso de tener una versión distinta de Python deberás descargar Python 3.11 del mismo enlace y utilizar la función de `py` para utilizar la versión correcto, p.ej.:

```bash
py -3.11 --version
```
Si obtienes algo como `Python 3.11.x` has instalado correctamente la versión necesaria, de lo contrario verifica que la carpeta donde instalaste Python 3.11 esté en el PATH.

## Clonar Repositorio

Clonar el repositorio con:

```bash
git clone https://github.com/uthynauta/fundamentos-llms.git
```

## Crear un ambiente virtual

Se deberá crear un ambiente de python, ya sea mediante Anaconda o bien como _venv_, la versión con la que se creo este repositorio es Python 3.11, y en caso de requerir aceleración de hardware es posible instalando las versiones correspondientes de `torch`, `torchvision` y `torchaudio`.

Para crear el ambiente virtual se puede navegar a la carpeta del repo:

```bash
cd fundamentos-llms
python -m venv fund-llms
```
Despues dependiendo de si se está trabajando en un sistema Windows o UNIX se puede correr:

```bash
.\fund-llms\Scripts\Activate.ps1
OR
sh ./fund-llms/Scripts/activate.sh
```

Posteriormente se debe activar el ambiente e instalar los paquetes incluidos en el archivo:

```bash
pip install -r requirements.txt
```

## Ejecución de los ejemplos

Para ejecutar los notebooks de Jupyter, desde línea de comandos correr:

```bash
jupyter lab
```

Esto abrirá una ventana nueva de su navegador predeterminado en donde podrá correr los ejemplos del repositorio utilizando el ambiente recientemente creado.
