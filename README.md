# Damián Bengochea

Desarrollo productos digitales, automatizaciones y sistemas web enfocados en resolver problemas operativos reales.

Construyo MVPs, herramientas internas y plataformas administrables con foco en:
- ejecución rápida
- UX clara
- arquitectura mantenible
- automatización
- integración con servicios reales

---

## Qué hago

- SaaS y MVPs
- Automatizaciones
- Sistemas internos
- Plataformas administrables
- Paneles administrativos
- PWAs
- Integraciones con APIs
- Bots y notificaciones
- Herramientas para e-commerce
- Directorios y marketplaces simples
- Sistemas con autenticación, pagos y roles
- Landing pages orientadas a conversión

---

## Productos y proyectos

### Quirvo — QR timbre + notificaciones + chat

Sistema de timbre QR con notificaciones y chat en tiempo real para edificios y casas.

Hoy ya funciona para un edificio real:

**visitante → timbre → notificación → chat → cierre automático**

#### Features

- Puertas/unidades (edificio/casa)
- Carga batch de unidades
- Roles: **PUERTA_ADMIN** / **UNIDAD_ADMIN** / **RESIDENTE**
- Preferencias por usuario: Push / Telegram / Ambos
- Timbre con geolocalización (geofence por radio)
- Eventos + chat persistente por evento
- Notificaciones: Telegram + Web Push/PWA
- Anti-ruido: cooldown + auto-cierre por limpieza
- Deep links desde Telegram hacia timbre/chat
- Realtime updates

#### Arquitectura / conceptos implementados

- Sistema orientado a eventos
- Roles y permisos
- Realtime communication
- Persistencia de eventos/mensajes
- Geofencing por radio
- Notificaciones multicanal
- PWA + Web Push
- Deep linking
- Limpieza automática de eventos
- Arquitectura fullstack mantenible

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
- Validación de rentabilidad
- Lógica orientada a sellers reales

#### Conceptos trabajados

- lógica comercial
- automatización de cálculos
- validación de márgenes
- UX orientada a velocidad
- integración de pagos/suscripciones
- arquitectura SaaS

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

Inspirado en un problema operativo real:
encontrar gente que trabaja “cuando otros descansan”.

#### Funcionalidades

- Listado público por rubros/categorías
- Buscador de proveedores
- Contacto directo por WhatsApp/email
- Solicitud para aparecer en el directorio
- Panel admin para gestionar:
  - proveedores
  - categorías
  - solicitudes
- Sistema de aprobación de proveedores
- Upload de documentación opcional
- Métricas de visitas y categorías más consultadas
- Sistema de autenticación
- Emails transaccionales

#### Arquitectura / conceptos implementados

- Next.js App Router
- Prisma ORM
- PostgreSQL / Supabase
- Auth.js / NextAuth
- Resend
- Supabase Storage
- Vercel
- Server Actions
- Panel administrativo privado
- Arquitectura fullstack mantenible

---

### Plataforma inmobiliaria administrable

Sistema web para inmobiliaria con catálogo de propiedades y panel privado de gestión.

#### Funcionalidades

- Listado público de propiedades
- Detalle de propiedad
- Filtros por operación/zona/tipo
- Panel admin privado
- Alta, edición y baja de propiedades
- Carga y administración de imágenes
- Gestión de datos comerciales
- Captura de consultas/leads
- Plataforma administrable orientada a uso real

#### Arquitectura / conceptos implementados

- Next.js App Router
- TypeScript
- Tailwind CSS
- Prisma ORM
- PostgreSQL / Supabase
- Auth.js / NextAuth
- Storage para imágenes
- Server Actions
- Arquitectura fullstack mantenible
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
- foco operativo antes que sobreingeniería

---

## Experiencia práctica

- Deploys productivos
- Integraciones reales con pagos y notificaciones
- Sistemas usados por usuarios reales
- Manejo de roles y permisos
- Arquitecturas fullstack mantenibles
- Desarrollo end-to-end
- Integración con APIs y servicios externos
- Gestión de autenticación y sesiones
- Automatizaciones
- PWAs y Web Push
- Integración de pagos
- Diseño de flujos operativos simples

---

## Enfoque

Me interesa construir productos útiles y sistemas mantenibles antes que sobreingeniería innecesaria.

Prioridad:
- velocidad de iteración
- claridad operativa
- UX simple
- automatización
- mantenimiento razonable
- resolver problemas reales

No me interesa complejidad innecesaria.
Prefiero sistemas simples, entendibles y que puedan mantenerse y evolucionar rápido.

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
- HTML
- CSS
- JavaScript
- PWA
- Web Push
- Responsive Design
- UX/UI orientada a conversión

### Backend

- Node.js
- Next.js App Router
- Server Actions
- API Routes
- Auth.js / NextAuth
- Prisma ORM
- Supabase
- PostgreSQL
- Row Level Security
- Validaciones de datos
- Roles y permisos
- Webhooks

### Base de datos / Storage

- PostgreSQL
- Supabase Database
- Supabase Storage
- Prisma Schema
- Migraciones / db push
- Relaciones entre entidades
- Modelado de datos

### Infraestructura / Deploy

- Vercel
- Cloudflare Pages
- Cloudflare DNS
- Supabase
- Variables de entorno
- Dominios personalizados
- Deploy productivo
- Debugging en producción

### Integraciones

- Telegram Bot API
- MercadoPago
- Resend
- Gmail / Email routing
- Web Push Notifications
- Deep links
- Webhooks
- APIs externas

### Herramientas

- Git
- GitHub
- GitHub Desktop
- VS Code
- Prisma Studio
- Supabase Dashboard
- Vercel Dashboard
- Cloudflare Dashboard
- Postman / pruebas de API

### Producto / Negocio

- MVPs
- SaaS
- Automatizaciones
- Paneles administrativos
- Sistemas internos
- Plataformas administrables
- Directorios
- Herramientas para e-commerce
- Flujos de pago
- Suscripciones
- UX simple orientada a usuarios reales

---

## Contacto

- Email: dbengotech@gmail.com