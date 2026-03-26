#  Proyecto Web: Galería de Animes

##  Descripción

Este proyecto consiste en una página web desarrollada en HTML5 y CSS, cuyo objetivo es mostrar información sobre distintos animes populares. Además, se implementa la gestión de imágenes mediante estilos CSS, cumpliendo con los requisitos solicitados en la actividad.

---

##  Objetivo de la Actividad

Aplicar estilos CSS a todas las imágenes del sitio web, asegurando que:

* Todas las imágenes sean modificadas mediante CSS
* Cada imagen tenga un tamaño diferente
* No se utilicen atributos HTML como `width` o `height`

---

##  Tecnologías Utilizadas

* HTML5
* CSS3

---

## Estructura del Proyecto

```
/proyecto
│── index.html
│── /assets
│    ├── /css
│    │     └── style.css
│    └── /img
│          ├── descarga.jpg
│          ├── ace.jpg
│          └── eva 01.jpg
```

---

## Gestión de Imágenes

Todas las imágenes del sitio fueron estilizadas utilizando CSS externo (`style.css`).

Se aplicaron las siguientes características:

* Tamaños distintos para cada imagen usando clases CSS
* Bordes redondeados (`border-radius`)
* Sombra (`box-shadow`)
* Efecto hover para mejorar la interacción del usuario

Ejemplo:

```css
.img1 {
    width: 150px;
}

.img2 {
    width: 250px;
}

.img3 {
    width: 350px;
}
```

---

##  Contenido de la Página

La página incluye:

* **Header** con navegación
* **Artículos** con información de animes:

  * Hunter x Hunter
  * One Piece
  * Evangelion

---

##  Conclusión

Se logró implementar correctamente la gestión de imágenes mediante CSS, cumpliendo con todos los requisitos solicitados. Además, se mejoró la presentación visual del sitio aplicando estilos adicionales.

---

##  Autor

Carlos Sepúlveda

---

