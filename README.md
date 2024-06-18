# Hogar y Confort Project

## Descripción
Este es el proyecto Django para "Hogar y Confort". Es una aplicación web diseñada para la venta de muebles y otros bienes de hogar.

## Configuración Inicial

Para ejecutar este proyecto localmente, sigue los siguientes pasos:

### Prerrequisitos
- Python 3.x
- pip
- virtualenv (opcional)

### Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/AlexOT03/Hogar-Confort
```


2. Navega al directorio del proyecto:

```bash
cd Hogar-Confort
```


3. (Opcional) Crea y activa un entorno virtual:

```bash
virtualenv venv source venv/bin/activate 
# En Windows usa: venv\Scripts\activate
```


4. Instala las dependencias:

```bash
pip install -r requirements.txt
```


5. Copia el archivo `.env.example` a `.env` y ajusta las variables de entorno según sea necesario.

6. Realiza las migraciones necesarias:

```bash
python manage.py migrate
```


7. Ejecuta el servidor de desarrollo:

```bash
python manage.py runserver
```


Ahora deberías poder acceder al servidor de desarrollo en [http://localhost:8000](http://localhost:8000).

## Licencia

Este proyecto está bajo la Licencia (en progreso). Consulta el archivo LICENSE.md para más detalles.