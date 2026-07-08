# FishMarket 🐟

Magazin online premium pentru pește și fructe de mare inspirat din experiența UI/UX a Samokat.

## 🚀 Tech Stack

### Frontend
- **Next.js 15** cu React 19
- **TypeScript**
- **Tailwind CSS** pentru styling
- **Framer Motion** pentru animații
- **Swiper.js** pentru carusele
- **GSAP** pentru animații avansate
- **Lucide Icons**

### Backend
- **Node.js** cu **Express**
- **Prisma** ORM
- **PostgreSQL** bază de date
- **Redis** pentru caching
- **JWT** autentificare cu refresh tokens
- **bcrypt** pentru hashing parolelor
- **Cloudinary** pentru upload imagini

### Funcții Suplimentare
- **PWA** - Suport Progressive Web App
- **SEO** - Optimizare SEO completă
- **Panou Admin** - Management conținut complet
- **Multi-limbă** - Română, Rusă, Engleză
- **Dark Mode** - Schimbare temă premium

## 📋 Structura Proiectului

```
fishmarket/
├── frontend/              # Aplicație Next.js 15
│   ├── src/
│   │   ├── app/          # App router
│   │   ├── components/   # Componente React
│   │   ├── lib/          # Utilitare
│   │   ├── hooks/        # Hook-uri personalizate
│   │   ├── styles/       # Stiluri globale
│   │   └── types/        # Tipuri TypeScript
│   ├── public/           # Fișiere statice
│   └── package.json
├── backend/               # Server Express
│   ├── src/
│   │   ├── routes/       # Rutele API
│   │   ├── controllers/  # Logica de afaceri
│   │   ├── middleware/   # Middleware Express
│   │   ├── models/       # Modele Prisma
│   │   ├── services/     # Servicii
│   │   └── utils/        # Funcții helper
│   ├── migrations/       # Migrații bază de date
│   └── package.json
├── docker-compose.yml    # Servicii Docker
└── .env.example
```

## 🚀 Instalare

### Condiții Prealabile
- Node.js 18+
- PostgreSQL 15+
- Redis 7+
- npm sau yarn

### Setup

1. **Clonează repository-ul**
   ```bash
   git clone https://github.com/Eugen779/fishmarket.git
   cd fishmarket
   ```

2. **Setup Variabile Mediu**
   ```bash
   cp .env.example .env.local
   ```

3. **Instalează Dependențe**
   ```bash
   # Frontend
   cd frontend && npm install && cd ..
   
   # Backend
   cd backend && npm install && cd ..
   ```

4. **Setup Bază de Date**
   ```bash
   cd backend
   npm run db:push
   npm run db:seed
   cd ..
   ```

5. **Start Development**
   ```bash
   npm run dev
   ```

   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000
   - Panou Admin: http://localhost:3000/admin

## 🔐 Credențiale Admin Implicite

- **Email**: admin@fishmarket.md
- **Parolă**: Admin123!

⚠️ Schimbă imediat în producție!

## 📦 Funcții

### Funcții Client
- ✅ Hero slider modern cu parallax
- ✅ Căutare live cu autocomplete
- ✅ Filtrare & sortare produse
- ✅ Coș cu vouchere
- ✅ Opțiuni multiple checkout (card, cash, transfer)
- ✅ Wishlist & favorite
- ✅ Recenzii & rating produse
- ✅ Produse vizualizate recent
- ✅ Infinite scroll
- ✅ Suport dark mode
- ✅ Cache offline PWA
- ✅ Suport multi-limbă

### Funcții Admin
- ✅ Management complet produse
- ✅ Management categorii cu ierarhie
- ✅ Tracked & management comenzi
- ✅ Insight clienți
- ✅ Dashboard analytics
- ✅ Management promoții & discounturi
- ✅ Management bannere
- ✅ CMS pentru toate paginile
- ✅ Notificări Email/SMS/Push
- ✅ Bibliotecă media cu optimizare
- ✅ Setări & configurare

## 🎨 Design System

### Culori
- **Primary**: Alb (#FFFFFF)
- **Secondary**: Navy Blue (#001F3F)
- **Accent**: Turcoaz (#17A2B8)
- **Gradient**: Navy la Turcoaz
- **Text**: Gri Închis (#333333)
- **Border**: Gri Ușor (#E8E8E8)

### Componente
- Efecte glass morphism
- Umbre subtile
- Animații netede
- Micro-interacțiuni
- Tipografie premium

## 📊 Date Demo

- 100 produse
- 20 categorii
- 15 bannere
- 25 promoții
- 50 recenzii
- 30 clienți test
- 50 comenzi test

## 🔍 SEO

- ✅ Meta tags & Open Graph
- ✅ XML Sitemap
- ✅ Robots.txt
- ✅ Schema.org markup
- ✅ Canonical URLs
- ✅ Optimizare performanță (Lighthouse 95+)

## 📱 Design Responsive

- Desktop
- Tabletă
- Mobile (iPhone & Android)
- Interacțiuni optimizate pentru touch

## 🚀 Deployment

### Frontend (Vercel)
```bash
npm i -g vercel
vercel
```

### Backend (Railway/Render)
```bash
# Consultă backend README pentru instrucțiuni deployment
```

## 📖 Documentație API

Consultă `backend/API.md` pentru documentația completă API.

## 🤝 Contributing

Fork repository-ul și creează o feature branch.

## 📄 Licență

Proiect privat - Toate drepturile rezervate.

## 📞 Support

Pentru probleme și întrebări, creează o issue pe GitHub.

---

**Făcut cu ❤️ pentru iubitorii de pește** 🐟
