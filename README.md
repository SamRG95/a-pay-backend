# A-Pay Backend

Backend para el sistema A-Pay desplegado en Railway.

## Instalación

```bash
npm install
```

## Configuración de la base de datos

```bash
npx prisma generate
npx prisma db push
```

## Variables de entorno

- `DATABASE_URL`: URL de la base de datos PostgreSQL
- `PORT`: Puerto del servidor (Railway lo configura automáticamente)

## Ejecutar

```bash
npm start
```

## Despliegue

Este backend está configurado para desplegarse en Railway. 