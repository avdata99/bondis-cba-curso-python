# Prueba de Flask para curso Python

Aplicación para mostrar información sobre el transporte
urbano de pasajeros de la ciudad de Córdoba.  
Los datos de origen están disponibles en el API de la
Ciudad de Córdoba en 
[cordobus.apps.cordoba.gob.ar](https://cordobus.apps.cordoba.gob.ar/tracking/api/internos-activos-ahora/)

## Instalar

Crear un entorno local, activarlo e instalar los requerimientos

```
python3 -m venv .python
source .python/bin/activate
pip install -r requirements.txt
```

Definir las variables de entorno antes de ejecutar la aplicacion Flask

```
FLASK_APP=app
# Si queremos que al cambiar código automaticamente se reinicie el servidor
# para aplicar los cambios
FLASK_ENV=development
```

Ejecutar la aplicaion Flask

```
flask run
```
