# 📊 Quantix AI — E-commerce Analytics SaaS

> **Plataforma de análisis de datos con IA para e-commerce**

[![Demo en Vivo](https://img.shields.io/badge/Demo-Live-green?style=flat-square&logo=vercel)](https://e-commerce-analytics-saas.vercel.app)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_2-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

---

## 🌐 Demo en vivo

**👉 [e-commerce-analytics-saas.vercel.app](https://e-commerce-analytics-saas.vercel.app)**

---

## 📋 Descripción

SaaS de inteligencia de negocio para tiendas online. Transforma datos de ventas, stock e inventario en insights accionables mediante dashboards interactivos y predicciones de IA.

### Características principales

- ✅ **Dashboard analítico** con gráficos interactivos (Recharts)
- ✅ **Predicciones de ventas** con Google Gemini AI
- ✅ **Segmentación de clientes VIP** con análisis de comportamiento
- ✅ **Alertas de stock** inteligentes con Machine Learning integrado
- ✅ **Multi-idioma** EN/ES/PT con sistema i18n completo
- ✅ **Estado global** con Zustand 5.x
- ✅ **Exportación de reportes** en CSV/PDF

---

## 🛠️ Stack Técnico

| Capa | Tecnología |
|---|---|
| **Framework** | Next.js 15 (App Router) |
| **Lenguaje** | TypeScript 5.x |
| **Estado** | Zustand 5.x |
| **Estilos** | Tailwind CSS 4.x · Framer Motion 11.x |
| **Charts** | Recharts 2.x |
| **Backend** | Supabase 2.x (PostgreSQL 16) |
| **AI** | Google Gemini API |
| **i18n** | Sistema propio EN/ES/PT |
| **Deploy** | Vercel |

---

## 🏗️ Arquitectura

```
┌────────────────────────────────────────────┐
│            Next.js 15 App Router            │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  │
│  │Dashboard │  │ Reports  │  │Settings  │  │
│  └──────────┘  └──────────┘  └──────────┘  │
│        ┌──────────────────────┐             │
│        │    Zustand Store     │             │
│        └──────────┬───────────┘             │
└─────────────────┼───────────────────────────┘
                  ▼
    ┌─────────────────────────┐
    │  Supabase · PostgreSQL  │
    │  Gemini AI Insights     │
    └─────────────────────────┘
```

---

> **Nota:** Este es un repositorio de exhibición. El código fuente completo es privado (producto comercial).
> Para consultas sobre licencias o desarrollo a medida: [diegofbis63@gmail.com](mailto:diegofbis63@gmail.com)
