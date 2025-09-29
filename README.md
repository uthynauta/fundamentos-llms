# Fundamentos sobre LLMs
Este es el repositorio oficial sobre el curso de Fundamentos sobre LLMs.

## Instalación

Se deberá crear un ambiente de python, ya sea mediante Anaconda o bien como _venv_, la versión con la que se creo este repositorio es Python 3.9

Posteriormente activar el ambiente e instalar los siguientes paquetes:

```bash
pip install packages\torch-2.4.1+cu124-cp311-cp311-win_amd64.whl
pip install packages\torchaudio-2.4.1+cu124-cp311-cp311-win_amd64.whl
pip install packages\torchvision-0.19.1+cu124-cp311-cp311-win_amd64.whl
pip install transformers
pip install scikit-learn
pip install huggingface_hub
pip install jupyterlab
```
Para mayor facilidad se incluye un archivo `requirements.txt` que instala las paqueterías necesarias activando el ambiente y corriendo:

```bash
pip install -r requirements.txt
```

Para ejecutar los notebooks de Jupyter, desde línea de comandos correr:

```bash
jupyter lab
```