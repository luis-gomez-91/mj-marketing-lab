# MJ Marketing Lab

Landing de **MJ Marketing Lab**: agencia digital enfocada en marketing en redes sociales, desarrollo web y soluciones digitales. Diseño con paleta blanco/slate y acento violeta, enfoque en performance.

## Stack

- **Astro** – Sitio estático
- **Tailwind CSS** – Estilos (paleta: blanco/slate + acento violeta)

## Cómo usar

```bash
npm install
npm run dev
```

Abre [http://localhost:4321](http://localhost:4321).

| Comando | Descripción |
|--------|-------------|
| `npm run dev` | Servidor de desarrollo |
| `npm run build` | Genera la carpeta estática para producción |
| `npm run preview` | Previsualiza la build de producción |

## Configuración

- **Formulario de contacto:** En `src/pages/index.astro` sustituye `YOUR_FORM_ID` en el `action` del `<form>` por tu ID de [Formspree](https://formspree.io) (o Netlify Forms / Getform).
- **WhatsApp:** En la parte superior de `src/pages/index.astro` cambia `WHATSAPP_NUMBER` por tu número (Ecuador: `593` + 9 dígitos, sin `+` ni espacios). El botón flotante y el enlace "Escribir por WhatsApp" usarán ese número.

## Contenido de la landing

1. **Mensaje principal** – Pregunta al emprendedor + "Quiero empezar"
2. **Problema** – "Empezar en redes puede ser difícil" + bullets
3. **Servicios** – Creación de redes, Reels, Publicidad, Consultoría
4. **Paquete Emprendedor Digital** – Incluye + precio $120–$150
5. **Beneficios** – Estrategia real, contenido profesional, enfoque emprendedores, acompañamiento
6. **Estrategia** – Resumen (Instagram, Reels/TikTok, WhatsApp)
7. **Contacto** – Nombre, Emprendimiento, Teléfono, Servicio + botón WhatsApp
8. **Botón WhatsApp flotante** – En esquina inferior derecha
