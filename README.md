# Dieguito-boquitas 😂

Página web interactiva con la foto original de Diego. Al hacer clic en su imagen, una capa animada simula que abre y cierra la boca.

## Ejecutar localmente

Requiere Node.js 18 o superior:

```bash
npm start
```

Abre `http://localhost:3000`.

## Desplegar en Railway

1. En Railway, crea un proyecto con **New Project → Deploy from GitHub Repo**.
2. Selecciona `maxlopeez15-png/Dieguito-boquitas`.
3. Railway detectará `package.json` y ejecutará `npm start`.
4. En **Settings → Networking**, genera un dominio público.

No requiere variables de entorno adicionales: el servidor utiliza automáticamente el puerto `PORT` que Railway le asigna.
