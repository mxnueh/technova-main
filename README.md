# technova-main · TechNova System

Sitio web de **TechNova**, empresa de tecnología ficticia: página de presentación y pantallas de registro e inicio de sesión (solo interfaz).

## 1. Descripción

Front-end estático con la landing de TechNova y sus pantallas de autenticación. Es la parte visual del sistema que se desarrolló en el repositorio [`floppy`](https://github.com/mxnueh/floppy).

## 2. Páginas

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Landing: hero, *Acerca de TechNova*, *¿Por qué elegir TechNova?*, servicios, equipo y proyectos |
| `Login.html` | Pantalla **Crear cuenta** |
| `SignIn.html` | Pantalla **Iniciar sesión** |

> Los nombres de `Login.html` y `SignIn.html` están intercambiados respecto a su contenido.

## 3. Tecnologías

- HTML · CSS

## 4. Uso

No requiere instalación. Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python -m http.server 8000
```

Los formularios no envían datos a ningún servidor.

## 5. Estructura

```
technova-main/
├── index.html
├── Login.html
├── SignIn.html
└── static/
    ├── css/    # style.css, LoginStyle.css, SignStyle.css
    └── img/    # Logo y fotos del equipo
```
