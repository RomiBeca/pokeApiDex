# ⚡ Pokédex Ultimate

Una Pokédex web interactiva, con estética **Dark Premium**, construida con **HTML, CSS y JavaScript puro**. Obtiene información de [PokéAPI](https://pokeapi.co/) y funciona sin instalar dependencias.

## ✨ Funcionalidades

- Catálogo de 1025 Pokémon (generaciones I–IX).
- Búsqueda por nombre o número, filtros por tipo y generación.
- Fichas con descripciones, habilidades, estadísticas, peso, altura y evoluciones.
- Favoritos y lista de capturados persistentes con `localStorage`.
- Comparador de estadísticas entre dos Pokémon.
- Modo claro/oscuro con preferencia guardada.
- Interfaz adaptable a móviles, tarjetas interactivas y paginación.
- Caché de solicitudes para reducir las peticiones repetidas.

## 🚀 Ejecutar localmente

1. Descomprime el ZIP.
2. Abre `index.html` en el navegador con conexión a internet.
3. Alternativamente, ejecuta un servidor local:

```bash
python -m http.server 8000
```

Abre `http://localhost:8000`.

## 🌍 Publicar en GitHub Pages

Sube los archivos `index.html`, `style.css`, `app.js` y `README.md` al directorio raíz del repositorio. Ve a **Settings → Pages → Deploy from a branch → main → /(root)**.

## 🧰 Tecnologías

**HTML5 · CSS3 · JavaScript (ES6+) · Fetch API · localStorage · PokéAPI**

## 📁 Estructura

```text
pokedex-ultimate/
├── index.html  # Estructura semántica e interfaz
├── style.css   # Diseño responsivo y temas
├── app.js      # API, filtros, favoritos y comparador
└── README.md   # Documentación
```

> Proyecto fan creado con fines educativos y de portafolio. Pokémon y sus personajes pertenecen a sus respectivos propietarios. Datos e imágenes suministrados por PokéAPI y PokeAPI/sprites.
