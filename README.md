# Mi primera web en la nube

Página personal de **Dario Rivera**, estudiante de Ingeniería de Sistemas (electiva Cloud Computing). Es su primer sitio web desplegado en la nube.

## Estructura del proyecto

```
mi-primera-web/
└─ Mi primera web/
   ├─ index.html          # Estructura de la página
   ├─ styles/
   │  └─ styles.css        # Estilos (tema "panel de despliegue")
   └─ img/
      └─ Dario.jpeg         # Foto de perfil
```

## Sobre el diseño

La página está pensada como un panel de despliegue: la foto de perfil se presenta como una ficha técnica con tres datos clave (carrera, electiva, estado) y un bloque tipo terminal simula el log de un `git push`, en línea con el hecho de que este sitio realmente vive en la nube.

- **Tipografía:** [Space Mono](https://fonts.google.com/specimen/Space+Mono) para titulares y datos técnicos, [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) para el cuerpo de texto.
- **Paleta:** azul-tinta profundo con acentos en ámbar y cian.
- **Responsive:** el layout se adapta desde escritorio hasta móvil.

## Cómo verla en tu máquina

1. Clona o descarga este repositorio.
2. Abre `Mi primera web/index.html` directamente en tu navegador, o sírvelo con un servidor local:
   ```bash
   cd "Mi primera web"
   python3 -m http.server 8000
   ```
3. Visita `http://localhost:8000` en tu navegador.

## Despliegue

Este proyecto es estático (HTML + CSS puro), por lo que puede desplegarse directamente en servicios como GitHub Pages, Netlify o Vercel sin necesidad de un proceso de build.

## Foto de perfil

Coloca tu fotografía en `Mi primera web/img/Dario.jpeg` (mismo nombre de archivo) para que se muestre correctamente en el círculo de la sección principal.

---

Hecho por Dario Rivera como parte de la electiva de Cloud Computing.