# Damián Bengochea

Desarrollo productos digitales, automatizaciones y sistemas web enfocados en resolver problemas operativos reales.

Construyo MVPs y herramientas internas con foco en:
- ejecución rápida
- UX clara
- arquitectura mantenible
- integración con servicios reales

---

## Qué hago

- SaaS y MVPs
- Automatizaciones
- Paneles administrativos
- PWAs
- Integraciones con APIs
- Sistemas internos para operaciones
- Bots (Telegram / notificaciones)
- Flujos con pagos y autenticación
- Plataformas administrables
- Herramientas para e-commerce

---

## Productos y proyectos

### Quirvo — QR timbre + notificaciones + chat

Hoy ya funciona para un edificio real:

**visitante → timbre → notificación → chat → cierre automático**

#### Features

- Puertas/unidades (edificio/casa) + carga batch de unidades
- Roles: **PUERTA_ADMIN** / **UNIDAD_ADMIN** / **RESIDENTE**
- Preferencias por usuario: Push / Telegram / Ambos
- Timbre con geolocalización (geofence por radio)
- Eventos + chat por evento (mensajes persistidos)
- Notificaciones: Telegram + Web Push/PWA
- Anti-ruido: cooldown + auto-cierre por limpieza
- Deep links desde Telegram a timbre/chat

#### Arquitectura / conceptos implementados

- Sistema orientado a eventos
- Realtime updates
- Geofencing por radio
- Roles y permisos
- Notificaciones multicanal
- Deep links
- Persistencia de eventos/mensajes
- Limpieza automática de eventos
- PWA + Web Push

➡️ Case study (sin código):  
https://github.com/BengoDamian/portfolio/blob/main/case-studies/quirvo.md

---

### Calculadora ML (MercadoLibre Pricing Calculator)

Webapp para calcular precio de venta según:
- costo
- margen
- comisiones
- cuotas
- descuentos

manteniendo rentabilidad real.

#### Funcionalidades

- Cálculo automático de precio objetivo
- Simulación de cuotas y descuentos
- Ajuste por comisión de MercadoLibre
- Control de margen final
- Lógica orientada a sellers reales

➡️ Case study (sin código):  
https://github.com/BengoDamian/portfolio/blob/main/case-studies/mercadolibre-pricing-calculator.md

---

### Orientador de precios / detección de oportunidades (WIP)

Herramienta orientada a vendedores de MercadoLibre para analizar productos, validar márgenes y detectar oportunidades comerciales.

#### Objetivo

Reducir decisiones manuales y acelerar validación de productos rentables.

#### Conceptos trabajados

- análisis de precios
- validación de márgenes
- lógica comercial
- automatización de cálculos
- enfoque seller-first

---

### Siempre de Guardia — Directorio administrable de proveedores

Plataforma web para encontrar proveedores y servicios disponibles fuera de horarios habituales.

#### Funcionalidades

- Listado público por rubros/categorías
- Buscador de proveedores
- Contacto directo por WhatsApp/email
- Solicitud para aparecer en el directorio
- Panel admin para gestionar proveedores, categorías y solicitudes
- Sistema de aprobación de proveedores
- Upload de documentación opcional
- Métricas de visitas y categorías más consultadas

#### Arquitectura / conceptos implementados

- Next.js App Router
- Prisma ORM
- PostgreSQL / Supabase
- Auth.js / NextAuth
- Resend para emails transaccionales
- Supabase Storage
- Vercel

---

### Plataforma inmobiliaria administrable

Sistema web para inmobiliaria con catálogo de propiedades y panel privado de gestión.

#### Funcionalidades

- Listado público de propiedades
- Detalle de propiedad
- Filtros básicos por operación/zona/tipo
- Panel admin privado
- Alta, edición y baja de propiedades
- Carga de imágenes
- Gestión de datos comerciales
- Captura de consultas/leads

#### Arquitectura / conceptos implementados

- Next.js App Router
- TypeScript
- Tailwind CSS
- Prisma ORM
- PostgreSQL / Supabase
- Auth.js / NextAuth
- Storage para imágenes
- Vercel

---

## Sistemas web y landings

También desarrollo:
- sitios institucionales
- landings orientadas a conversión
- paneles administrativos
- sistemas internos
- directorios
- plataformas administrables

Siempre priorizando:
- claridad
- velocidad
- mantenimiento razonable
- UX simple

---

## Experiencia práctica

- Deploys productivos
- Integraciones reales con pagos y notificaciones
- Sistemas usados por usuarios reales
- Manejo de roles y permisos
- Arquitecturas fullstack mantenibles
- Desarrollo end-to-end
- Integración con APIs y servicios externos

---

## Enfoque

Me interesa construir productos útiles y sistemas mantenibles antes que sobreingeniería innecesaria.

Prioridad:
- velocidad de iteración
- claridad operativa
- UX simple
- automatización
- mantenimiento razonable

---

## Portfolio público

- Repo:
  https://github.com/BengoDamian/portfolio

---

## Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- PWA / Web Push

### Backend / Base de datos

- Supabase
- PostgreSQL
- Prisma ORM
- Auth.js / NextAuth
- Server Actions / APIs

### Infraestructura

- Vercel
- Cloudflare

### Integraciones

- Telegram Bot API
- MercadoPago
- Resend

---

## Contacto

- Email: dbengotech@gmail.com