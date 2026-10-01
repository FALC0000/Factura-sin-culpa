# Factura sin Culpa — Landing Page

Landing page oficial para el taller **Factura sin Culpa** impartido por **Saulibeth Rivas**, mentora y coach de bienestar y emprendimiento femenino.

- **Próximo Encuentro:** Jueves 17 de Octubre
- **Modalidad:** Online en Vivo (Grupo Reducido)
- **Dominio Destino:** `factura-sin-culpa.falc0dev.me`

---

## 🎨 Características de Diseño & Marca

- **Identidad Visual:** Alineada 100% al Manual de Marca de Saulibeth Rivas (Paleta Rojo `#971B25`, Vinotinto `#660A11`, Crema `#EFE6E3`, Nude `#E0BCAF`, Sage `#9AA793`).
- **Tipografía:** Google Fonts *Pinyon Script* para títulos ceremoniales de marca, *Cormorant Garamond* para subtítulos editoriales y *Nunito* para textos corridos y UI.
- **Favicon Oficial:** Sello circular monograma con la "S" de Saulibeth Rivas adaptado en multi-resolución (`favicon.ico`, `favicon-32x32.png`, `favicon-16x16.png`, `apple-touch-icon.png`).
- **Previsualización de Links (WhatsApp & Redes Sociales):**
  - Imagen Open Graph panorámica (1200x630 px, ~70 KB) con zona segura centrada para evitar recortes.
  - Imagen cuadrada dedicada (800x800 px, ~65 KB) para miniaturas en chats móviles de WhatsApp.
  - Etiquetas Open Graph y Twitter Cards completas con fecha 17 de Octubre, descripción persuasiva y tipografía de alta fidelidad.

---

## 📁 Estructura del Proyecto

```text
factura-sin-culpa/
├── index.html            # Landing page completa y responsive
├── vercel.json           # Configuración de caché, headers de seguridad y URLs limpias
├── .gitignore            # Archivos ignorados por git
├── README.md             # Documentación del proyecto
└── assets/
    ├── favicon.ico       # Favicon multi-capa (16, 32, 48, 64)
    ├── favicon-16x16.png # Favicon estándar navegador
    ├── favicon-32x32.png # Favicon retina navegador
    ├── apple-touch-icon.png # Icono iOS / marcadores móviles
    ├── logo.png          # Logotipo horizontal oficial transparente
    ├── sello.png         # Sello circular oficial transparente
    ├── saulibeth.png     # Retrato fotográfico oficial de Saulibeth Rivas
    ├── og-image.jpg      # Banner social 1200x630 px (<100KB)
    └── og-whatsapp.jpg   # Banner cuadrado 800x800 px (<100KB)
```

---

## 🚀 Despliegue en Vercel & Dominio Personalizado

1. Subir al repositorio en GitHub:
   ```bash
   git add .
   git commit -m "feat: landing page Factura sin Culpa para el 17 de octubre"
   git push -u origin main
   ```
2. Importar el repositorio en **Vercel**.
3. Asignar el dominio personalizado:
   - **Subdominio:** `factura-sin-culpa.falc0dev.me`
   - **Registro DNS en Namecheap:**
     - **Tipo:** `CNAME`
     - **Host:** `factura-sin-culpa`
     - **Valor (Target Vercel):** El destino individualizado generado por Vercel para el proyecto (por ejemplo `cname.vercel-dns.com` o el hash individual asignado por Vercel).
