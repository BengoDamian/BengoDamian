# Damián Bengochea

Diseño y construyo **sistemas tecnológicos para negocios digitales**.  
Arquitectura escalable, automatización con criterio y productos reales en producción.

Mi enfoque no es “hacer bots”.  
Es diseñar sistemas que **no se rompan cuando crecen**.

---

## En qué me especializo

- Arquitectura de SaaS y sistemas internos
- Automatización con control de riesgo
- Integraciones (APIs, bots, notificaciones, pagos)
- Autenticación, permisos y control de acceso
- Diseño con fallback y reducción de single points of failure

---

## Productos (código privado)

### Quirvo — Acceso con QR + eventos + notificaciones (MVP)
Implementado en un edificio real.

**Flujo:** visitante → timbre → evento → notificación → chat → cierre automático  
**Claves:** modelo orientado a eventos, roles granulares, canales de notificación desacoplados (Telegram/Web Push), anti-spam, deep links, geofence.

➡️ Case study: `portfolio / Quirvo`

---

### Calculadora ML — Motor de pricing MercadoLibre (privado)
Capa de decisión para proteger margen con comisiones, cuotas y descuentos.

**Enfoque:** motor parametrizable, reglas de negocio separadas de UI, base lista para escalar a SaaS multiusuario.

➡️ Case study: `portfolio / Calculadora ML`

---

## Filosofía de diseño

- Todo flujo crítico necesita estados, visibilidad y fallback.
- Los permisos y accesos son parte de la arquitectura, no un detalle.
- Escalar es simplificar, no conectar herramientas sin control.

---

## Stack

Next.js · TypeScript · Tailwind  
Supabase (Auth + Postgres) · Vercel/Cloudflare · Telegram Bot API · PWA/Web Push

---

## Contacto

dbengotech@gmail.com
