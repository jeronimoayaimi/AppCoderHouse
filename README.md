
# App Bosque Barber House

## Descripción
App Bosque Barber House es una aplicación desarrollada en Django destinada a la gestión de una barbería. Incluye funcionalidades para la reserva de turnos, gestión de clientes y empleados, y más.

## Características
- **Gestión de turnos:** Permite a los clientes reservar turnos en línea.
- **Gestión de clientes y empleados:** Registra y administra la información de los clientes y empleados.
- **Base de datos:** Utiliza una base de datos SQLite para almacenar la información.

## Estructura del proyecto

AppCoderHouse/
├── barberia/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── barberia.db
├── manage.py
└── README.md


## Instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/jeronimoayaimi/AppCoderHouse.git
   cd AppCoderHouse
   ```

2. Crear un entorno virtual y activarlo:
   ```bash
   python -m venv env
   source env/bin/activate  # En Windows usar `env\Scripts\activate`
   ```

3. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

4. Realizar las migraciones:
   ```bash
   python manage.py migrate
   ```

5. Ejecutar el servidor de desarrollo:
   ```bash
   python manage.py runserver
   ```

## Uso
Accede a la aplicación en [http://127.0.0.1:8000](http://127.0.0.1:8000) y podrás comenzar a utilizar las funcionalidades de gestión de la barbería.

## Comentarios
Es una primera versión cumpliendo con los requisitos de la presentación-entrega nro 3. 

## Desarrollador
Jerónimo Martínez
