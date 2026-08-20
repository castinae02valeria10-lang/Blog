# Mi Blog Personal

Blog personal hecho en HTML puro, usando tablas para organizar el contenido por secciones.

## 📖 Descripción

Página web tipo blog donde se comparten distintos aspectos de la vida de la autora: experiencias personales, baile, participación en organizaciones juveniles, su camino en programación y su gusto por la lectura.

## 🗂️ Secciones

| Sección | Ancla | Contenido |
|---|---|---|
| La primera vez | `#primera` | Reflexión sobre una serie que marcó a la autora |
| Renacer Venezolano | `#baile` | Experiencia en una academia de baile/folclor |
| Academia Joven | `#academia` | Participación en organización juvenil de la Araucanía |
| Programación | `#prog` | Experiencia estudiando la especialidad de programación |
| Literatura | `#libros` | Gusto por la lectura |
| Contáctame | `#contac` | Datos de contacto y redes |

## 🛠️ Tecnologías

- **HTML5**: estructura semántica (`header`, `nav`, `section`, `article`)
- Navegación interna mediante anclas (`<a href="#id">`)
- Tablas (`<table>`) para dar formato a cada bloque de contenido

## 📁 Estructura de carpetas esperada

```
proyecto/
├── index.html
└── IMG/
    ├── primeravez.jpg
    ├── VVzu.jpeg
    ├── reunionACDM.jpeg
    ├── confia.jpeg        (nota: usada sin la carpeta IMG/, revisar ruta)
    └── libro.jpg
```

## ▶️ Cómo verlo

1. Descarga o clona la carpeta del proyecto.
2. Asegúrate de que las imágenes referenciadas estén dentro de `IMG/` con el mismo nombre usado en el código.
3. Abre `index.html` con tu navegador (doble clic o "Abrir con" → navegador).

## 📝 Notas / posibles mejoras

- La imagen de la sección **Programación** usa la ruta `confia.jpeg` sin el prefijo `IMG/`; probablemente deba ser `IMG/confia.jpeg` para que cargue igual que las demás.
- Actualmente el diseño se apoya en `bgcolor` (atributo HTML antiguo). Si más adelante quieres modernizarlo, se puede migrar a un archivo `.css` externo sin cambiar el contenido.
- El correo y celular están publicados directamente en el HTML; si el blog quedará visible públicamente en internet, vale la pena pensar si quieres dejarlos así de expuestos o usar un formulario de contacto en su lugar.

---
*Hecho con 💘 — 08/06/2026*