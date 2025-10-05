# Gyrate Netcom – Online Grocery Shopping Platform

> **Domain:** E‑commerce (Online Grocery Shopping)  
> **Position:** Software Developer  
> **Author:** Sagarika Chakraborty — *Full Stack .NET Engineer | React.js | Web API | SQL Server*

**Gyrate Netcom** is an end‑to‑end online grocery platform built on **ASP.NET MVC 5** with **Entity Framework** and **SQL Server**. It delivers product catalogue management, search, shopping cart & checkout, order tracking, role‑based access (admin/vendor/customer), and responsive UI. The project followed a **3‑layer architecture** (BLL/DAL/Models) and used **TFS** for version control and CI/CD. Reporting was produced via **RDLC**.

---

## ✨ Key Features
- **Customer**: Register/Login, browse categories, search, add to cart, checkout, order history & tracking.
- **Admin Portal**: Manage products, categories, inventory, pricing, orders, users; RDLC invoices/reports.
- **Vendor**: Role‑based catalogue & inventory updates (optional).
- **UX**: jQuery + AJAX for live cart, filters, and seamless interactions; responsive design.

---

## 🧱 Technology Stack
- **Framework**: ASP.NET MVC 5, C#, .NET Framework
- **Data**: Entity Framework (Code‑First/Database‑First), LINQ, SQL Server 2019
- **Frontend**: Razor Views, jQuery, AJAX, Bootstrap (responsive)
- **Reporting**: RDLC Reports (Invoices, Sales, Inventory)
- **DevOps**: TFS (Team Foundation Server) for version control & deployment

---

## 📁 Repository Structure
```
.
├─ README.md
└─ docs
   ├─ HLD.md
   ├─ LLD.md
   └─ architecture.png
```

---

## 🚀 Quick Start (Dev)
Update `Web.config` connection string and run the MVC project:
```xml
<connectionStrings>
  <add name="GroceryDb" connectionString="Data Source=.;Initial Catalog=GyrateNetcom;Integrated Security=True;TrustServerCertificate=True" providerName="System.Data.SqlClient"/>
</connectionStrings>
```
Apply EF migrations (if Code‑First) and seed data for categories/products.

---

## 🧭 Documentation
- **HLD**: [`/docs/HLD.md`](docs/HLD.md) — architecture, flows, quality attributes
- **LLD**: [`/docs/LLD.md`](docs/LLD.md) — endpoints/actions, DTOs, schema, sequences, error codes
- **Diagram**: [`/docs/architecture.png`](docs/architecture.png)

---

## 👩‍💻 Credits
**Sagarika Chakraborty** — MVC modules (Catalog, Cart/Checkout, Orders, Profiles/Feedback), EF/LINQ performance, RDLC reports, TFS CI/CD.
