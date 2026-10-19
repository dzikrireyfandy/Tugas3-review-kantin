# Tugas 3 Authentication, Authorization, & Data Validation: Review Kantin

Project backend API menggunakan Node.js, TypeScript, dan Drizzle ORM yang dilengkapi dengan sistem autentikasi JWT, validasi input menggunakan Zod, pembatasan hak akses (*Role-Based Access Control* & *Object-Level Ownership*), serta pengamanan password menggunakan *Bcrypt*.


---

##  Struktur Folder Project

```text
tugas3-review-kantin/
├─ package.json
├─ tsconfig.json
├─ drizzle.config.ts
├─ .env.example
├─ sql/
│  ├─ 00-setup-mixed-mode.sql        
│  ├─ 01-create-database-and-user.sql  
│  ├─ 02-schema.sql                    
│  └─ 03-seed.sql                    
└─ src/
   ├─ index.ts          
   ├─ db/
   │  ├─ schema.ts           
   │  └─ index.ts           
   ├─ middlewares/          
   ├─ dtos/                 
   ├─ repositories/         
   ├─ services/             
   ├─ controllers/          
   └─ docs/                
