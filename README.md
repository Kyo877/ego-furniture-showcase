# ego-furniture-showcase
#the website i made with AI to a furniture company
#  E Go Furniture & Interior Design — Digital Catalog & Web Platform

[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=for-the-badge&logo=cloudflare)](https://egofurniture.ego-ykwong077.workers.dev/)
[![Deployment](https://img.shields.io/badge/Hosted_on-Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare)](https://egofurniture.ego-ykwong077.workers.dev/)
[![Status](https://img.shields.io/badge/Source_Code-Private_Commercial-blue?style=for-the-badge&logo=github)](#)

> A full-featured digital catalog, interior design portfolio, and quotation inquiry platform built for **E Go Furniture & Interior Design** (Kota Tinggi & Ulu Tiram, Johor). 

🔗 **Live Website**: [https://egofurniture.ego-ykwong077.workers.dev/](https://egofurniture.ego-ykwong077.workers.dev/)  
🔒 **Repository Notice**: *This repository serves as a public project showcase. The production source code, admin management system, and backend APIs are maintained in a private repository (`ego-website-production`) to protect commercial data and business logic.*

---

## 🌟 Project Overview

**E Go Furniture & Interior Design** required a modern, fast, and accessible web platform to showcase their bespoke carpentry, interior renovation projects, and material catalogs to clients across Malaysia. 

This platform bridges the gap between browsing offline material sample books and online consultation—allowing customers to explore materials, switch seamlessly between three languages, and request quotations directly.

---

## ✨ Key Features

### 1. 🗂️ Interactive Material & Product Catalog
Structured digital showcase covering core interior and furniture categories:
- **Sintered Stone (岩板)**
- **Fluted Panels (格栅板)**
- **Wallpaper (壁纸)**
- **Curtains (窗帘)**
- **Doors (门类) & Bespoke Carpentry**

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
