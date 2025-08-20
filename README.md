#  WorkOrder Portal

**WorkOrder Portal** es una aplicación web fullstack desarrollada con **TypeScript, Next.js, React y Node.js**.  
Permite a pequeñas y medianas empresas gestionar **órdenes de trabajo, tickets y solicitudes de clientes** de forma ágil y organizada.

![WorkOrder Portal Demo](https://via.placeholder.com/1000x400.png?text=WorkOrder+Portal+Demo)

---

##  Características

- 📌 **Gestión de Tickets:** crea, asigna y actualiza estados de órdenes de trabajo.  
- 👥 **Roles de usuario:** cliente, agente y administrador.  
- 💬 **Comentarios y archivos adjuntos** por ticket.  
- 📊 **Dashboard interactivo** con métricas y estado general.  
- 📂 **Exportación de reportes** en CSV.  
- 🔑 **Autenticación segura** con Auth.js (NextAuth).  
- ⚡ **API REST** documentación clara.  

---

## Stack Tecnológico

- **Frontend:** Next.js (App Router) · React · TailwindCSS · shadcn/ui  
- **Backend:** Node.js · Prisma ORM · MongoDB  
- **Auth:** Auth.js (NextAuth)  
- **Estado:** React Query · Zod (validación)  
- **Testing:** Vitest · Playwright  
- **DevOps:** Docker · GitHub Actions (CI/CD)  
- **Storage:** AWS S3 / MinIO  

---

##  Instalación y Uso

```bash
# 2. Instalar dependencias
pnpm install

# 3. Configurar variables de entorno
# Copia el archivo .env.example a .env y define:
# DATABASE_URL="URL"
# NEXTAUTH_SECRET="clave-super-secreta"

# 4. Ejecutar migraciones y seed
pnpm prisma migrate dev
pnpm prisma db seed

# 5. Levantar el servidor
pnpm dev

```

## Test

```Bash
# Unit tests
pnpm test

# End-to-End tests
pnpm e2e
```

---

## Estructura del proyecto

```
workorder-portal/
├─ app/                # Páginas Next.js (App Router)
│  ├─ dashboard/       # Dashboard principal
│  ├─ tickets/         # Tickets (lista, detalle, nuevo)
│  └─ api/             # Rutas API REST
├─ components/         # Componentes UI reutilizables
├─ prisma/             # Esquema y migraciones
├─ tests/              # Unit y e2e tests
├─ .github/workflows/  # CI/CD con GitHub Actions
└─ README.md
```


## 📜 Licencia

Este proyecto está licenciado bajo la **MIT License**.  

Puedes usarlo, modificarlo y distribuirlo libremente, incluso con fines comerciales, siempre que mantengas el aviso de copyright y la licencia correspondiente.  

📄 Para más detalles revisa el archivo [LICENSE](./LICENSE).



