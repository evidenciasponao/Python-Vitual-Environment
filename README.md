# Python-Vitual-Environment
Manual about Python Virtual Environment

This Manual was created to try explain how to create Virtual Environment in Python

1.Open the folder with Visual Studio Code and open a Terminal and type: Python -m venv venv

![image](https://user-images.githubusercontent.com/98203936/180690017-a7b8be4a-e70a-4dae-bd7d-5a5276a870f0.png)

2.Visual Studio Code show you a windows and select YES

![image](https://user-images.githubusercontent.com/98203936/180690426-76e6fa91-9300-42ab-92ed-0fd3fc0ac203.png)

Puesta en marcha
Abre una terminal de comandos
Navega hasta la raíz del proyecto donde quieres listar las dependencias
Ejecuta
pip freeze > requirements.txt
Abre el archivo requirements.txt creado, este listará todas las dependecias de paquetes así como la versión del mismo que tu proyecto requiere para funcionar:
Para instalar esta lista de dependencias en cualquier otra instalación de Python puedes ejecutar

pip install -r requirements.txt


