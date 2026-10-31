# HumINT MVP

Sitio web estático de HumINT, preparado para publicarse directamente desde GitHub con Vercel.

## Estructura

- `dist/`: web completa lista para servir.
- `vercel.json`: indica a Vercel que publique el contenido de `dist/`.
- No hay dependencias, compilación ni variables de entorno obligatorias.

## Vista previa local

Desde la raíz del proyecto:

```bash
python3 -m http.server 4173 --directory dist
```

Después abre `http://localhost:4173`.

## Subir a GitHub

```bash
git init
git add .
git commit -m "Publicar HumINT MVP"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

## Publicar con Vercel

1. En Vercel, selecciona **Add New → Project**.
2. Importa el repositorio de GitHub.
3. Mantén **Framework Preset: Other**.
4. `vercel.json` configurará automáticamente `dist` como directorio de salida.
5. Pulsa **Deploy**.

Las rutas como `/como-funciona`, `/precios` y `/empezar-revision` ya incluyen su propio `index.html` y funcionan como páginas estáticas.
