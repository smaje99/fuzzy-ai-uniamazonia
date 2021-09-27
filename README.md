# fuzzy-ai-uniamazonia

Ejercicio presentado en la asignatura Inteligencia Artificial en el septimo semestre de Ingenieria de Sistemas de la Universidad de la Amazonia.

## Setup
Paso 1. Clonar el repositorio
```
git clone git@github.com:smaje99/fuzzy-ai-uniamazonia.git
```

Paso 2. Crear el entorno virtual e instalar las dependencias
```
virtualenv venv
```
```
venv\Scripts\activate
```
```
pip install -r requirements.txt
```

Paso 3. Crear el kernel para Jupyter Notebook con nuestro entorno y salier del entorno virtual
```
python -m ipykernel install --user --name fuzzy --display-name "Python (fuzzy)"
```
```
deactivate
```

Paso 4. Ejecutar Jupyter Notebook
```
jupyter notebook
```

Estos comandos estan establecido para trabajar en Windows
