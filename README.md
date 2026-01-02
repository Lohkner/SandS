[README.txt](https://github.com/user-attachments/files/24403526/README.txt)
# ⚔️ S&S: Crónicas Antiguas

**Generador y Hoja de Personaje Digital para el sistema de rol Stars & Sorcery.**

> *Una herramienta de estilo "Old School" (OSR) diseñada para gestionar la identidad, estadísticas y equipo de tus aventureros de forma automática, sin perder la sensación de papel y lápiz.*

## 📜 Descripción del Proyecto

**S&S: Crónicas Antiguas** es una aplicación web progresiva (PWA) de una sola página (SPA) construida con HTML5, CSS3 y JavaScript puro (Vanilla JS).

Su objetivo es simplificar la creación de personajes para *Stars & Sorcery (v4.5)*, automatizando todos los cálculos matemáticos (modificadores, carga, CA, reservas) mientras se mantiene una estética inmersiva de "grimorio antiguo".

## ✨ Características Principales

* **🧮 Motor Táctico Automatizado:** Cálculo en tiempo real de Puntos de Vida, Umbral de Carne, Adrenalina, Ingenio y Clase de Armadura (CA) basándose en atributos y equipo.
* **🛡️ Gestión de Equipo Dinámica:** Sistema de inventario que calcula el peso (Slots) y ajusta la CA según el tipo de armadura (Ligera, Media, Pesada) y escudos, respetando los límites de Destreza.
* **🎲 Generador de NPCs/PJs:** Botón de "Aleatorizar" que crea un personaje legal y completo (incluyendo talentos y equipo) en un solo clic.
* **💾 Persistencia de Datos:** Sistema de Guardado y Carga local (`localStorage`) para mantener tus personajes seguros en tu dispositivo sin necesidad de bases de datos externas.
* **📱 PWA & Offline First:** Diseñada para instalarse como una App nativa en Android/iOS y funcionar perfectamente sin conexión a internet.
* **🎨 Estética OSR:** Interfaz gráfica personalizada con paleta de colores de pergamino y tinta, tipografías clásicas y diseño responsive.

## 🚀 Cómo Usar

### Opción A: Versión Online (GitHub Pages)
Puedes acceder a la última versión estable directamente desde el navegador:
(https://github.com/Lohkner/SandS)

### Opción B: Instalación Local
1.  Descarga el repositorio.
2.  Abre el archivo `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge).
3.  ¡Listo! No requiere instalación de servidores ni dependencias.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica.
* **CSS3:** Variables CSS (`:root`) para la gestión de temas de color (Tinta/Pergamino) y diseño Grid/Flexbox.
* **JavaScript (ES6):** Lógica de negocio, manipulación del DOM y gestión del `localStorage`.
* **PWA:** `manifest.json` y Service Workers para caché y funcionamiento offline.

## 📖 Reglas Soportadas

La aplicación incluye la base de datos completa de:
* **Linajes:** Humano, Enano, Elfo, Sintético, Aesir, etc.
* **Arquetipos:** Audaz (Luchador), Sutil (Experto), Sagaz (Adepto).
* **Equipo:** Armas (cuerpo a cuerpo y distancia), Armaduras y Escudos con sus propiedades especiales.
* **Talentos:** Árboles completos de Acero, Adrenalina, Astucia, Fuente y General.

---

*Proyecto desarrollado para facilitar las sesiones de juego de Stars & Sorcery.*
