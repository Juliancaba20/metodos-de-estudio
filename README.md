# Métodos de estudio

Catálogo gratuito y sin fines de lucro de métodos de estudio, con el nivel de respaldo de la evidencia en cada uno. Sitio estático hecho con [Astro](https://astro.build).

## Desarrollo

```bash
npm install
npm run dev       # servidor local en http://localhost:4321
npm run build     # genera la carpeta dist/
```

## Contenido

Cada método es un archivo JSON en `src/metodos/`. Se muestran en orden alfabético por nombre de archivo, por eso llevan un prefijo numérico.

| Campo | Descripción |
|-------|-------------|
| `n` | Nombre del método |
| `q` | Descripción en una línea |
| `l` | Nivel de respaldo: 0 variable, 1 limitado, 2 moderado, 3 sólido |
| `t` | Situaciones: `poco`, `memorizar`, `comprender`, `grupo` |
| `e` | Esfuerzo |
| `u` | Para qué sirve |
| `p` | Pasos (lista) |
| `f` | Dónde falla |
| `r` | Qué dice la evidencia |

Para agregar o corregir un método, edite o cree un archivo en esa carpeta y abra un pull request indicando la fuente.

## Publicación

El proyecto se despliega en Vercel sin configuración adicional: framework Astro, comando `npm run build`, carpeta de salida `dist`.
