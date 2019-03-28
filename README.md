# keras-tutorial

Tutorial sobre Tensorflow+Keras

## Uso

Tienes dos opciones: usar tu propia instalación de Python o usar Docker para no tocar nada en tu sistema.

### Con Docker

```
git clone https://github.com/fdavidcl/keras-tutorial
cd keras-tutorial
docker run --rm -p 8888:8888 -v $(pwd):/home/jovyan/work \
  -e JUPYTER_ENABLE_LAB=1 -e JUPYTER_TOKEN=libreim \
  jupyter/tensorflow-notebook
```

Accede a Jupyter Lab en `http://localhost:8888/?token=libreim`.

### Con Python

```
git clone https://github.com/fdavidcl/keras-tutorial
cd keras-tutorial
python3 -m pip install --user tensorflow jupyterlab
python3 -m jupyter lab
```