---
name: mj-landing
description: Guides changes to the MJ Marketing Lab landing (Astro, Tailwind). Use when editing the landing, adding or editing service pages, updating copy, or working on index.astro, Layout.astro, or files under src/pages/servicios/.
---

# MJ Marketing Lab – Project skill

## Stack

- **Astro 4** (static), **Tailwind CSS**
- No backend nor database; forms use Formspree (or similar) and WhatsApp link

## Structure

- **Layout** (`src/layouts/Layout.astro`): Nav (logo, Servicios dropdown, Paquete, Beneficios, Solicitar asesoría), then `<slot />`. Dropdown links to `/servicios/*`. Nav hides on scroll down, reappears on scroll up.
- **Home** (`src/pages/index.astro`): Sections in order — hero (100vh minus nav, padding via wrapper), problema, 4 service blocks (full-height, bold colors), paquete (pricing grid), beneficios, estrategia, contacto. WhatsApp float button.
- **Service pages**: `src/pages/servicios/[nombre].astro` (e.g. desarrollo-web.astro). Each uses Layout, has title/description, “Volver al inicio” link, short copy, CTA to `/#contacto`.

## Conventions

- **Language**: All user-facing copy in Spanish (Spain/LATAM). Audience: emprendedores, Ecuador.
- **Colors**: Paleta basada en mauve de Tailwind: acento `mauve-500`/`mauve-600` para CTAs, enlaces y focus. Bloques de servicios alternan `mauve-600` y `mauve-700`. Hero con gradiente mauve-50/mauve-100; tarjetas de precios emerald (pago único) vs mauve (mensual).
- **Sections**: Full width (`w-full`). First section height `h-[calc(100vh-4rem)]`; others `min-h-screen` where needed. Padding applied via wrapper in hero so image and text respect it.
- **Forms**: Formspree `action` placeholder in index; WhatsApp number constant at top of index. No DB.

## When to use this skill

- Adding or editing a service page.
- Changing nav, dropdown, or global layout.
- Updating hero, pricing, benefits, or contact section.
- Keeping new sections or components consistent with existing style and structure.