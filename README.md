# 🌊 Fondo de Bikini — Página de Personajes

Página web estática, hecha con **HTML y CSS puros**, que presenta a los personajes de la serie animada *Bob Esponja Pantalones Cuadrados* en tarjetas con un diseño de "océano moderno y vibrante".

🔗 **Ver el sitio:** https://juanfmorenoa777.github.io/Fondo_Bikini_Web/

## ✨ Características

- Barra de navegación fija (sticky) con degradado azul–turquesa.
- Banner con borde en forma de ola, dibujado con un SVG dentro del CSS.
- Título con texto en degradado (`background-clip: text`).
- Grilla de 8 tarjetas de personajes que se acomoda sola según el ancho de pantalla (`repeat(auto-fit, minmax())`).
- Animaciones al pasar el mouse sobre tarjetas, enlaces y redes sociales.
- Pie de página con enlaces, contacto e íconos de redes.
- Diseño responsive con tres puntos de quiebre (`768px`, `600px` y `480px`).

## 👥 Personajes

Bob Esponja · Patricio Estrella · Calamardo · Don Cangrejo · Arenita Mejillas · Plankton · Gary · Señora Puff

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica (`nav`, `header`, `main`, `section`, `article`, `footer`) |
| CSS3 | Flexbox, Grid, variables CSS, transiciones, `@media` |
| Google Fonts | Tipografías *Baloo 2* y *Quicksand* |
| GitHub Pages | Publicación del sitio |

## 📁 Estructura del proyecto

```
HTML1 BOB SPONJA/
├── index.html
├── README.md
├── CSS/
│   └── style.css
└── img/
    ├── logo.png
    ├── logo.webp
    ├── banner.jpeg
    ├── bob esponja.webp
    ├── patricio.webp
    ├── calamardo.png
    ├── don_Cangrejo.jpeg
    ├── arenita.jpeg
    ├── Plankton.jpeg
    ├── Gary.webp
    └── señora.webp
```

> **Nota:** GitHub Pages distingue mayúsculas de minúsculas. La carpeta debe llamarse `CSS` y el archivo principal `index.html`, tal como aparecen arriba.

## 🚀 Cómo ejecutarlo en tu computador

1. Clona el repositorio:
   ```bash
   git clone https://github.com/juanfmorenoa777/Fondo_Bikini_Web.git
   ```
2. Entra a la carpeta:
   ```bash
   cd Fondo_Bikini_Web
   ```
3. Abre `index.html` con doble clic o con la extensión **Live Server** de Visual Studio Code.

No necesita instalar nada ni usar un servidor, solo un navegador. Para que se carguen las fuentes de Google Fonts hace falta conexión a internet.

## 🌐 Publicación en GitHub Pages

1. En el repositorio, ve a **Settings → Pages**.
2. En **Build and deployment**, elige la rama `main` y la carpeta `/(root)`.
3. Guarda y espera unos minutos hasta que aparezca la URL del sitio.

## 🔮 Próximos pasos

- [ ] Crear las páginas `personajes.html`, `episodios.html` y `contacto.html` (los enlaces del menú ya apuntan a ellas).
- [ ] Reemplazar los enlaces de redes sociales (`#`) por los perfiles reales.
- [ ] Agregar un correo de contacto real en el pie de página.

## 👤 Autor

Hecho con 💛 por **Juan Felipe Moreno**
GitHub: [@juanfmorenoa777](https://github.com/juanfmorenoa777)

## ⚖️ Aviso

Proyecto con fines educativos y sin ánimo de lucro. Los personajes, nombres e imágenes de *Bob Esponja Pantalones Cuadrados* pertenecen a sus respectivos titulares de derechos.
