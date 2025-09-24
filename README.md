# 📻 La Nación Radio – Mobile App

**English**

Mobile application developed for La Nación Radio, the radio and podcast branch of La Nación, the largest news company in Venezuela. The project included the design and implementation of a new mobile experience for news, podcasts, radio stations, reels, companies, and ads integration.

**Español**

Aplicación móvil desarrollada para La Nación Radio, la división de radio y podcasts de La Nación, el noticiero más grande de Venezuela. El proyecto incluyó el diseño e implementación de una nueva experiencia móvil para noticias, podcasts, emisoras de radio, reels, empresas y anuncios personalizados.

---

## 🌍 Overview / Descripción

**English**

The app integrates the multimedia ecosystem of La Nación Radio, combining live radio, podcasts, news, reels, company directories, and ads in one single experience. A splash screen ensures proper controller loading, with retry logic in case of connection errors. The interface highlights the brand identity with a frosted-glass style app bar, custom banners, and a persistent mini-player across all views.

**Español**

La app integra el ecosistema multimedia de La Nación Radio, combinando radio en vivo, podcasts, noticias, reels, directorio de empresas y anuncios en una sola experiencia. Incluye una pantalla de carga inicial con lógica de reintento en caso de errores de conexión. La interfaz destaca la identidad de la marca con un app bar estilo vidrio esmerilado, banners personalizados y un mini-reproductor persistente en todas las vistas.

---

## ✨ Features / Características

**English**

- ⏳ Splash screen with error handling (retry on failed loading after 30s).

- 📰 News view: categories, infinite scroll with “show more”, in-app webview.

- 🎙️ Radio & Podcasts: modal details (hosts, schedules, topics) + mini-player.

- 📻 Live Radio Banner: quick access to main podcast stream.

- 🏢 Companies view: search, category filters, detail modal with contact info.

- 🎬 Reels & YouTube integration (latest IG reels and YT video).

- 📊 Ads integration: intercalated personalized banners across all sections.

- 🎨 Custom AppBar with frosted-glass blur effect.

- 📱 Bottom navigation: Home, Radio, News, Companies.

**Español**

- ⏳ Pantalla de carga con manejo de errores (reintento tras 30s si falla).

- 📰 Vista de Noticias: categorías, scroll infinito con “mostrar más”, webview interno.

- 🎙️ Radio y Podcasts: detalles en modal (locutores, horarios, descripción) + mini-player.

- 📻 Banner de Radio en Vivo: acceso rápido al podcast principal.

- 🏢 Vista de Empresas: buscador, filtros de categorías, detalle con horarios y contactos.

- 🎬 Integración Reels & YouTube (últimos reels de IG y video más reciente de YT).

- 📊 Integración de Anuncios: banners personalizados intercalados en cada sección.

- 🎨 AppBar personalizado con efecto blur estilo vidrio esmerilado.

- 📱 Navegación inferior: Inicio, Radio, Noticias y Empresas.

---

## 🛠️ Tech Stack / Tecnologías

- **Framework:** Flutter (Dart)

- **Backend:** WordPress REST API (integración directa)

- **Audio:** Just Audio / Audio Handler

- **Design:** Custom UI (Material + Frosted Glass)

- **Ads:** Custom ad manager integration

---

## 📂 Project Structure / Estructura del Proyecto
```text
assets/
 ├── audio/
 ├── fonts/
 ├── icons/
 ├── images/
 └── .env
lib/
 ├── main.dart
 ├── app/
 │   ├── app_state.dart
 │   └── splash_wrapper.dart
 ├── config/
 │   ├── app_theme.dart
 │   ├── constants.dart
 │   ├── custom_nav_style.dart
 │   ├── env_constants.dart
 │   └── text_styles.dart
 ├── utils/
 │   └── responsive_values.dart
 ├── widgets/
 │   ├── companies/...
 │   ├── radio/...
 │   ├── reels/...
 │   ├── ad_banner.dart
 │   ├── connection_error_dialog.dart
 │   ├── custom_bottom_navigation_bar.dart
 │   └── ...
 └── dashboard/
     ├── controllers/...
     ├── models/...
     └── views/...
```

---

## 📖 Case Study / Estudio de Caso

**English**

The project was delivered to La Nación Radio as part of their digital transformation. The app reinforced their position as Venezuela’s leading news group by extending content beyond traditional news into radio, podcasts, and digital advertising.

**Español**

El proyecto fue entregado a La Nación Radio como parte de su transformación digital. La aplicación reforzó su posición como el grupo de noticias más importante de Venezuela, expandiendo el contenido más allá de las noticias tradicionales hacia radio, podcasts y publicidad digital.

---

## 📈 Future Improvements / Mejoras Futuras

- 🔗 Push notifications for breaking news and live shows.

- 📱 Offline mode for downloaded podcasts.

- 🧪 Automated tests for controllers and API logic.

---

## 📜 License / Licencia

**English**

This project was developed for La Nación Radio (Venezuela). Source code available for reference, not for commercial redistribution.

**Español**

Este proyecto fue desarrollado para La Nación Radio (Venezuela). Código fuente disponible solo con fines de referencia, no para redistribución comercial.
