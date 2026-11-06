# Patito Boquitas 🐥

Página web interactiva que muestra únicamente la animación GIF de Patito Boquitas. Al hacer clic en el GIF, la animación vuelve a comenzar.

## Ejecutar localmente

Requiere Node.js 18 o superior:

```bash
npm start
```

Abre `http://localhost:3000`.

## Desplegar en Railway

1. Conecta el repositorio `maxlopeez15-png/Dieguito-boquitas`.
2. Railway detectará `package.json` y ejecutará `npm start`.
3. En **Settings → Networking**, genera un dominio público.

No requiere variables de entorno adicionales: el servidor utiliza automáticamente el puerto `PORT` que Railway le asigna.
