# BackFarmacia

## Descripción del Proyecto

BackFarmacia es una aplicación backend para la gestión de farmacias. Este proyecto permite administrar inventario de medicamentos, gestionar clientes, procesar pedidos y mantener un registro de transacciones.

## Características Principales

- Gestión de inventario de medicamentos
- Administración de clientes
- Sistema de pedidos y ventas
- Registro de transacciones
- Autenticación y autorización de usuarios
- API RESTful para integración con frontend

## Herramientas de Desarrollo

### Lenguaje y Framework
- **Node.js** - Runtime de JavaScript
- **Express.js** - Framework web para Node.js
- **Python** - (Opcional) Para scripts y utilidades

### Base de Datos
- **PostgreSQL** - Sistema de gestión de base de datos relacional
- **MongoDB** - (Opcional) Para datos no estructurados

### Herramientas de Desarrollo
- **npm** - Gestor de paquetes para Node.js
- **Git** - Control de versiones
- **Docker** - Containerización de la aplicación
- **Postman** - Prueba de APIs

### Testing y Calidad
- **Jest** - Framework de testing
- **ESLint** - Linter para JavaScript
- **Prettier** - Formateador de código

### Otros
- **Dotenv** - Gestión de variables de entorno
- **Bcrypt** - Encriptación de contraseñas
- **JWT** - Autenticación con tokens

## Instalación

1. Clonar el repositorio
```bash
git clone https://github.com/Bernalpas/backfarmacia.git
cd backfarmacia
```

2. Instalar dependencias
```bash
npm install
```

3. Configurar variables de entorno
```bash
cp .env.example .env
```

4. Ejecutar migraciones de base de datos
```bash
npm run migrate
```

## Uso

Iniciar el servidor en modo desarrollo:
```bash
npm run dev
```

Iniciar el servidor en producción:
```bash
npm start
```

## Estructura del Proyecto

```
backfarmacia/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── services/
├── tests/
├── config/
├── .env.example
├── package.json
└── README.md
```

## Contribución

Para contribuir al proyecto:
1. Crear una rama nueva (`git checkout -b feature/nueva-funcionalidad`)
2. Realizar cambios y hacer commits
3. Push a la rama (`git push origin feature/nueva-funcionalidad`)
4. Crear un Pull Request

## Licencia

Este proyecto está bajo la licencia MIT.

## Contacto

Para preguntas o sugerencias, contactar al equipo de desarrollo.
