# Hoja de vida web — Darío Rivera

Hoja de vida / carta de presentación como futuro Ingeniero de Sistemas, publicada en GitHub y desplegada en Vercel. Proyecto correspondiente al **Reto 1 — GitHub y Despliegue**.

**URL pública:** [https://mi-primera-web-dun.vercel.app/](https://mi-primera-web-dun.vercel.app/) — desplegada en Vercel.

## Contenido de la página

- Nombre completo y rol: **Darío Sebastián Rivera Sáenz** — Ingeniero de Sistemas en formación, último semestre.
- Perfil profesional.
- Experiencia laboral y académica (Transportadora de los Andes, Cuartel de Bombermans, CodeMaster, ROLAGRO).
- Educación (USTA Tunja, SENA, bachillerato técnico).
- Habilidades y tecnologías, agrupadas por área.
- Enlaces a [LinkedIn](https://www.linkedin.com/in/dario-rivera-3a674636a) y [GitHub](https://github.com/DarioRiverah), y correo de contacto.

## Estructura del proyecto

```
mi-primera-web/
├─ index.html      # Estructura de la página
├─ styles.css      # Estilos
├─ img/
│  └─ Dario.jpeg    # Foto de perfil
└─ README.md
```

## Cómo verla en tu máquina

```bash
git clone https://github.com/DarioRiverah/mi-primera-web.git
cd mi-primera-web
python3 -m http.server 8000
```
Luego abre `http://localhost:8000`.

## Despliegue en Vercel

1. Importa el repositorio en Vercel (New Project → Import Git Repository).
2. Framework preset: **Other** (es HTML/CSS puro, sin build).
3. Como `index.html` está en la raíz del repo, **no hace falta configurar Root Directory**.
4. Deploy. Vercel entrega la URL pública — en este caso [mi-primera-web-dun.vercel.app](https://mi-primera-web-dun.vercel.app/).

## Evidencias

- Pantallazo 1 — Repositorio en GitHub: ![Repositorio](Mi%20primera%20web/img/GitHubCapture.png)
- Pantallazo 2 — Deploy exitoso en Vercel: ![Deploy](Mi%20primera%20web/img/DeployVercel.png)
- Pantallazo 3 — Página funcionando en la URL pública: ![Página](Mi%20primera%20web/img/DeployWeb.png)

---

Entrega individual — Electiva Cloud Computing.