# Crear un entorno virtual

## Creación de entorno virtual en WSL2

* Ejecutar en terminal: ``python3 -m venv env``

  ```
     python3 -m venv env 
  ```

![image](Imagenes/CreacionDeCarpeta.PNG)

## Activar entorno

* Ejecutar en terminal ``source env/bin/activate``

  ```
     env\Scripts\activate 
  ```

![image](Imagenes/ActivarEntorno.PNG)

## Desactivar entorno

* Ejecutar en terminal ``deactivate``

  ```
     deactivate 
  ```

![image](Imagenes/Desactivar.png)

## Instalar una biblioteca

* Con el entorno activado ejecutamos en la terminal ``pip install python-dateutil``

  ```
     pip install python-dateutil
  ```

![image](Imagenes/InstallBiblioteca.png)

* Un mensaje de salida dice que está instalando correctamente, y termina con la siguiente oración:

  ```
  Successfully installed python-dateutil-2.8.2 six-1.16.0
  ```

