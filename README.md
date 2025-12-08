# RoomieMatch

**RoomieMatch** es una aplicación web diseñada para ayudar a las personas a encontrar su compañero de piso ideal. Permite crear perfiles, explorar perfiles de otros usuarios, gestionar anuncios de habitaciones o pisos, enviar mensajes privados y dejar reseñas.

---

## Índice

- [Características](#características)
- [Demo](#demo)
- [Instalación](#instalación)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Características

- Registro e inicio de sesión de usuarios.
- Creación y edición de perfil personal (nombre, edad, ciudad, bio, presupuesto, tags).
- Búsqueda de compañeros de piso mediante filtros de tags y presupuesto.
- Publicación y gestión de anuncios de habitaciones o pisos.
- Sistema de "me gusta" para guardar perfiles favoritos.
- Mensajería interna entre usuarios para coordinar la convivencia.
- Sistema de reseñas y calificaciones para usuarios.

---

## Demo

> La aplicación puede ejecutarse localmente abriendo `index.html` en un navegador moderno compatible con módulos ES.  
> **Nota:** Todos los datos se guardan en `localStorage` para simular una base de datos.

---

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/roomiematch.git
````

2. Abrir el archivo `index.html` en tu navegador:

> Se recomienda utilizar navegadores como Chrome, Edge o Firefox para evitar problemas con módulos ES.

3. Opcional: Para un entorno más avanzado, servir la aplicación usando un servidor local (por ejemplo, `Live Server` en VSCode) para evitar problemas de CORS con módulos ES.

---

## Estructura del proyecto

```
RoomieMatch/
│
├─ index.html           # Archivo principal de la aplicación
├─ style.css            # Estilos globales
├─ logo.png             # Logo de la aplicación
├─ profile1.png, ...    # Imágenes de perfiles de ejemplo
├─ listing1.png, ...    # Imágenes de anuncios de ejemplo
├─ icon-*.png           # Iconos utilizados en la UI
└─ README.md            # Documentación del proyecto
```

> Todos los scripts están integrados dentro de `index.html` para evitar problemas de carga de módulos locales.

---

## Tecnologías utilizadas

* **HTML5 & CSS3**: Estructura y estilos.
* **JavaScript (ES6+)**: Lógica y manejo del DOM.
* **[Lit-HTML](https://lit.dev/)**: Renderizado de templates dinámicos.
* **LocalStorage**: Almacenamiento de datos simulando una base de datos.

---

## Uso

1. Abrir la aplicación en un navegador.
2. Crear una cuenta o iniciar sesión con un usuario existente.
3. Explorar perfiles o anuncios disponibles.
4. Aplicar filtros de búsqueda según tus preferencias.
5. Dar "me gusta" a perfiles que te interesen.
6. Enviar mensajes a otros usuarios para coordinar la convivencia.
7. Publicar y gestionar tus propios anuncios.
8. Escribir reseñas sobre otros usuarios con los que hayas compartido piso.

---

## Contribuciones

Si deseas contribuir a RoomieMatch:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit.
4. Envía un pull request describiendo tus mejoras o correcciones.

---

## Licencia

Este proyecto está bajo la licencia **MIT**.
Ver [LICENSE](LICENSE) para más información.
