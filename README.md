# App de Requisiciones · GHC

- `index.html`: app del residente (celular, Chrome).
- `compras.html`: app de Compras / Admin (PC).

Base: Supabase "GHC - DataBase", esquema `ops`. Diseño completo en el proyecto "Apps GHC" → `Requisiciones - Diseño.md`.

## Publicar en GitHub Pages (repositorio privado, GitHub Pro)
1. Crea el repositorio privado `ghc-requisiciones` y sube estos dos archivos a la raíz.
2. Settings → Pages → Source: "Deploy from a branch", rama `main`, carpeta `/ (root)` → Save.
3. Ligas:
   - Residentes: `https://<usuario>.github.io/ghc-requisiciones/`
   - Compras: `https://<usuario>.github.io/ghc-requisiciones/compras.html`

Nota: en GitHub Pro, un sitio de Pages hecho desde un repositorio privado sigue siendo **visible para cualquiera que tenga la liga**. Lo que queda privado es el código del repositorio, no la página publicada.

## Primer acceso
1. Supabase → Authentication → Users → Add user → `cuatlo4@gmail.com`, con tu contraseña y "Auto Confirm User".
2. Entra a `compras.html` → Usuarios → 🔑 Contraseña para cada persona. Cambia a `compras` el rol de quien vaya a usar la app de Compras.
