# 🛋️ E Go Furniture & Interior Design — Digital Catalog & Web Platform

[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=for-the-badge&logo=cloudflare)](https://egofurniture.ego-ykwong077.workers.dev/)
[![Deployment](https://img.shields.io/badge/Hosted_on-Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare)](https://egofurniture.ego-ykwong077.workers.dev/)
[![AI Assisted](https://img.shields.io/badge/Development-AI--Assisted-8A2BE2?style=for-the-badge&logo=sparkles)](#)
[![Status](https://img.shields.io/badge/Source_Code-Private_Commercial-blue?style=for-the-badge&logo=github)](#)

> An AI-assisted commercial digital catalog, interior design portfolio, and quotation inquiry platform built for **E Go Furniture & Interior Design** (Kota Tinggi & Ulu Tiram, Johor). 

🔗 **Live Website**: [https://egofurniture.ego-ykwong077.workers.dev/](https://egofurniture.ego-ykwong077.workers.dev/)  
🔒 **Repository Notice**: *This repository serves as a public project showcase. The production source code, admin management system, and backend APIs are maintained in a private repository (`ego-website-production`) to protect commercial data and business logic.*

---

## 🌟 Project Overview

**E Go Furniture & Interior Design** required a modern, fast, and accessible web platform to showcase their bespoke carpentry, interior renovation projects, and material catalogs to clients across Malaysia. 

Developed through an **AI-augmented engineering workflow**, this platform bridges the gap between browsing offline material sample books and online consultation—allowing customers to explore materials, switch seamlessly between three languages, and request quotations directly.

---

## 🤖 AI-Assisted Development Workflow

This project demonstrates how modern AI tools can be leveraged to accelerate full-stack commercial web delivery from concept to production:

- **Rapid UI/UX Prototyping & Code Generation**: Utilized AI to iterate on responsive layouts, modern CSS styling, and interactive catalog components.
- **Admin System & Logic Implementation**: Collaborated with AI to architect the custom back-office admin panel, state management, and data handling routines.
- **Trilingual Localization (i18n)**: Leveraged AI to assist in translating and standardizing industry-specific interior design & material terminology across **English**, **Chinese (中文)**, and **Bahasa Melayu**.
- **Debugging & Edge Deployment**: Used AI-assisted troubleshooting to optimize script performance and streamline deployment onto Cloudflare Workers.

---

## ✨ Key Features

### 1. 🗂️ Interactive Material & Product Catalog
Structured digital showcase covering core interior and furniture categories:
- **Sintered Stone**
- **Fluted Panels**
- **Wallpaper**
- **Curtains**
- **Doors & Bespoke Carpentry**

### 2. Trilingual Interface (i18n Support)
- Full multi-language support tailored for the Malaysian market: **English**, **中文 (Chinese)**, and **Bahasa Melayu (Malay)**.
- Dynamic language switching with unified terminology across product catalogs and UI components.

### 3. Interior Design Inspiration & Portfolio
- Curated gallery displaying residential and commercial interior design case studies, helping clients visualize real-world space applications.

### 4. Custom Admin Panel (Protected Backend)
- Dedicated back-office content management system allowing administrators to dynamically manage product listings, update material categories, upload imagery, and edit multilingual copy without touching code.

### 5. Streamlined Inquiry & Quotation Flow
- Integrated customer consultation and quotation request workflow for rapid client follow-ups across branches.

### 6. Edge Performance & SEO Optimization
- Deployed on **Cloudflare Workers** for ultra-low latency and global CDN edge caching.
- Verified and indexed via **Google Search Console** with semantic HTML structure and localized metadata.

---

## 🛠️ Tech Stack & Architecture

- **Frontend**: HTML5, Modern Responsive CSS, Vanilla JavaScript
- **Development Methodology**: AI-Assisted Software Engineering & Prompt-Driven Prototyping
- **Localization**: Custom Trilingual State Management (`EN` / `ZH` / `MS`)
- **Edge Hosting & Routing**: Cloudflare Workers
- **Content Management**: Custom Admin Dashboard & Secure Backend API *(Private)*
- **Search & Indexing**: Google Search Console Integration

```text
[ Client Browser (EN / ZH / MS) ]
               │
               ▼  HTTPS / Edge Caching
[ Cloudflare Workers (egofurniture.ego-ykwong077.workers.dev) ]
               │
               ├─► Public View: Product Catalogs, Portfolios & Inquiry Routing
               │
               └─► Protected Route: Admin Panel & Content Management API (Private)
