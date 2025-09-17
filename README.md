# 💅 Aqua Nail Studio – Mis primeros pasos en Frontend

**Live:** https://migdtg.github.io/PaginaWebTestAguaNailStudio/  
**Stack:** HTML5 + CSS3 + Bootstrap 5  · Google Fonts · Bootstrap Icons

> Proyecto del integrador politecnico internacional : una web informativa-comercial para un salón de uñas.
> Quise enfocarme en **claridad**, **responsivo** y **accesibilidad** básica con Bootstrap.

---

## 🎯 Objetivos
- Mostrar **servicios** con **precios** y CTA “Reservar”.
- Incluir **multimedia**: galería de imágenes, **video** embebido y **audio** con tips.
- Practicar **HTML semántico**, **Bootstrap 5** y **CSS** propio (tokens en `:root`).
- Publicar en **GitHub Pages** como primera experiencia de deploy.

---

## ✨ Qué incluye
- **Navbar** sin JS (móvil con `<details>`, desktop ≥992px).
- **Hero** con imagen responsive.
- **Servicios** (cards con precio + botón).
- **Galería** responsiva (miniaturas cuadradas con `aspect-ratio`).
- **Video** (YouTube en `ratio 16:9`) y **Audio** (HTML5).
- **Tips** & Tendencias (cards informativas).
- **Contacto** (email/teléfono).
- Accesibilidad: `alt` descriptivo, **skip-link**, foco visible, contraste revisado.
- SEO on-page: `<title>`, `<meta description>`, Open Graph básico.

---

## 🧱 Estructura

index.html
assets/    
├─ css/  
│ └─ main.css
├─ img/  
│ └─ (...imágenes del sitio)  
├─ audio/  
│ └─ tips.mp3 (si aplica)  
└─ video/  
└─ (reservado)  

---

## 🛠️ Cómo correrlo localmente
1. Clona o descarga el repo.
2. Abre `index.html` en tu navegador  
   *(o usa la extensión “Live Server” en VS Code para autorecarga)*.

---

## 🚀 Deploy (GitHub Pages)
1. Subí `index.html` y `assets/` a la **raíz** del repo.  
2. Settings → **Pages** → Source: *Deploy from a branch* → Branch: `main` → Folder: `/ (root)` → **Save**.  
3. Listo: se genera la URL pública (arriba).

---

## 🧩 Decisiones técnicas (en simple)
- **Sin JavaScript:** el menú móvil usa `<details>` → accesible y suficiente para este MVP.
- **Imágenes de cards**: normalizadas con `object-fit: cover` + `aspect-ratio` para que queden uniformes.
- **Tipografía:** serif para títulos, sans para lectura (Google Fonts). Script solo para acento del brand.
- **Tokens CSS:** colores/espaciados en `:root` para cambiar paleta fácil.
- **Performance básico:** `loading="lazy"` en imágenes de cards; `preconnect` a Google Fonts; `display=swap`.

---

## 🖼️ Evidencias (capturas)
> Agrega capturas en `/assets/img/` y enlázalas aquí.

- **Home / Hero (desktop):**  
  ![Hero desktop](assets/img/captura-hero-desktop.png)
- **Servicios (desktop y móvil):**  
  ![Servicios desktop](assets/img/captura-servicios.png)
  ![Servicios móvil](assets/img/captura-servicios-movil.png)
- **Galería + Video + Audio + Tips:**  
  ![Galería](assets/img/captura-galeria.png)
  ![Video](assets/img/captura-video.png)
  ![Audio](assets/img/captura-audio.png)
  ![Tips](assets/img/captura-tips.png)
- **Contacto:**  
  ![Contacto](assets/img/captura-contacto.png)

---

## ✅ Checklist de calidad
- [x] HTML5 semántico (header/nav/main/section/footer)
- [x] Bootstrap 5 por CDN y CSS propio
- [x] Responsive móvil/tablet/desktop
- [x] Accesibilidad básica (alt, foco, contraste)
- [x] SEO on-page y Open Graph
- [x] Deploy en GitHub Pages

---

## 🧪 Cosas que aprendí (log personal)
- Arreglar **rutas/extension** (`.jpeg` vs `.jpg`) es clave para que nada “desaparezca” al publicar.
- Con **`object-fit: cover` + `aspect-ratio`** pude uniformar imágenes sin JS.
- El menú con `<details>` me salvó de escribir JS y funciona bien en móvil.
- GitHub Pages exige `index.html` en la **raíz**: si está dentro de una carpeta, no carga.

---

## 📌 Roadmap (próximos pasos)
- [ ] Formulario de contacto accesible (validación de Bootstrap).
- [ ] Optimizar imágenes (WebP + `srcset` real en el hero).
- [ ] Mejorar logo (PNG transparente o SVG).
- [ ] Página “Nosotros” y más contenido educativo.

---

## 🧾 Notas de versión (changelog breve)
- **v0.1** – Estructura base + navbar + hero.  
- **v0.2** – Servicios (cards con precios).  
- **v0.3** – Galería, video y audio.  
- **v0.4** – Tips + ajustes de tipografías/colores.  
- **v0.5** – Deploy en GitHub Pages, limpieza de rutas.

---## 📌 Notas de avance

- Quité `fixed-top` del header para que no tape contenido en móvil.
- Reduje el tamaño del logo en móvil (28px) y desktop (36px).
- Corregí rutas de imágenes (`.jpeg` vs `.jpg`) para que carguen en GitHub Pages.
- Deploy inicial en GitHub Pages funcionando:  
  https://migdtg.github.io/PaginaWebTestAguaNailStudio/


## 🧑‍💻 Créditos
- **Bootstrap** y **Bootstrap Icons** (CDN).
- **Google Fonts** (tipografías).
- Imágenes: propias y de referencia (temporalmente).  
  > Si alguna es de terceros, se reemplazará por material propio en las siguientes versiones.
