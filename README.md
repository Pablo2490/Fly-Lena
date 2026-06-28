# ✈️ Fly Lena

**Fly Lena** es una aplicación web de búsqueda y reserva de vuelos, desarrollada como proyecto académico. Permite a los usuarios buscar vuelos por origen, destino, fechas, cantidad de pasajeros y clase, visualizar ofertas destacadas y navegar por distintas secciones del sitio.

---

## 🌐 Deploy

https://flylenna.netlify.app/

---

## 🗂️ Estructura del proyecto

```
Fly-Lena/
├── index.html                        # Página principal (home)
├── main.js                           # Lógica principal (buscador, validaciones)
├── navbar.js                         # Navbar dinámica generada por JS
├── footer.js                         # Footer dinámico generado por JS
├── estilos_index_home.css            # Estilos del home
├── estilos_navbar_&_footer.css       # Estilos de navbar y footer
├── assets/                           # Recursos generales
├── img/                              # Imágenes (logo, banner, carrusel, promos)
├── estilos/                          # Estilos adicionales globales
└── pages/
    ├── checkout/
    │   ├── confirmacion.html         # Página de confirmación de compra
    │   ├── confirmacion.js
    │   ├── estilos_confirmacion.css
    │   ├── estilos_pagos.css
    │   ├── estilos_pasajeros.css
    │   ├── pago.html                 # Página de pago
    │   ├── pago.js
    │   ├── pasajeros.html            # Carga de datos de pasajeros
    │   └── pasajeros.js
    ├── detalle-de-vuelo/
    │   ├── detalles.html             # Detalle de vuelo seleccionado
    │   ├── detalles.js
    │   └── styles.css
    ├── ofertas/
    │   ├── ofertas.html              # Página de ofertas completas
    │   ├── ofertas.js
    │   └── styles.css
    ├── pages_footer/
    │   ├── contacto.html             # Página de contacto
    │   ├── contacto.js
    │   ├── estilos_Contacto.css
    │   ├── estilos_FAQ.css
    │   ├── estilos_Historia.css
    │   ├── historia.html             # Historia de la empresa
    │   └── preguntas_frecuentes.html # FAQ
    ├── perfil_de_usuario/
    │   ├── perfil_de_usuario.html    # Perfil del usuario
    │   ├── perfil_de_usuario.js
    │   ├── estilos_PerfilUsuario.css
    │   ├── reservas.html             # Reservas del usuario
    │   ├── reservas.js
    │   └── reservas.CSS
    ├── registro_&_login/
    │   ├── login.html                # Inicio de sesión
    │   ├── login.js
    │   ├── registro_de_cuenta.html   # Registro de nuevo usuario
    │   ├── registro.js
    │   ├── estilos_crear_cuenta.css
    │   └── estilos_ingresar.css
    └── resultados-de-busqueda/
        ├── filtro-1.html             # Resultados y filtros de búsqueda
        ├── resultados.js
        └── styles.css
```

---

## 🚀 Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura del sitio |
| CSS3 | Estilos y diseño responsivo |
| JavaScript (Vanilla) | Lógica, validaciones, componentes dinámicos |
| Font Awesome | Íconos |
| Google Fonts (Inter) | Tipografía |
| SweetAlert2 | Alertas y notificaciones |

---

## ⚙️ Funcionalidades

- 🔍 **Buscador de vuelos** con campos de origen, destino, fechas, pasajeros y clase.
- 🔄 **Modo ida y vuelta / solo ida** con toggle interactivo.
- ✅ **Validaciones en tiempo real** de todos los campos del formulario.
- 🎠 **Carrusel de ofertas** destacadas (CSS puro, sin librerías).
- 🧭 **Navbar dinámica** generada con JavaScript para usuario on/off.
- 🦶 **Footer dinámico** generado con JavaScript.
- 💼 **Sección de beneficios** (mejor precio, pago seguro, atención 24/7, millas).
- 📄 **Página de ofertas** completa.

---

## 👥 Creador

| Pablo Buttazzoni | [@Pablo2490](https://github.com/Pablo2490) |

---

## 📌 Estado del proyecto

🟡 En desarrollo y constante actualización — proyecto académico

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos.
