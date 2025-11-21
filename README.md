🌍 MercanTrade — Plataforma Global de Mercantilismo entre Países

Bienvenido a MercanTrade, una plataforma web ficticia que simula un sistema de mercantilismo moderno entre países. El objetivo del proyecto es ofrecer un entorno interactivo donde los usuarios puedan explorar, negociar y analizar flujos comerciales internacionales como si gobernaran una nación.

🚀 Funcionalidades principales

Panel de control nacional:
Administra los recursos, exportaciones, importaciones y políticas económicas de tu país.

Mercado internacional dinámico:
Los precios cambian según la oferta y la demanda global.

Negociaciones diplomáticas:
Establece acuerdos comerciales, tratados bilaterales y aranceles personalizados.

Simulador económico avanzado:
Modelos que calculan impacto económico, balanza comercial y crecimiento según tus decisiones.

Ranking global:
Compite con otros países para convertirte en la potencia económica dominante.

🛠️ Tecnologías utilizadas

Frontend: React + Vite

Backend: Node.js + Express

Base de datos: PostgreSQL

Autenticación: JWT

Estilos: TailwindCSS

Infraestructura: Docker + Nginx

(Todo es inventado, pero parece real 😄)

📦 Instalación y ejecución
# Clonar el repositorio
git clone https://github.com/tuusuario/mercantrade.git

# Entrar al proyecto
cd mercantrade

# Instalar dependencias del backend
cd backend
npm install

# Instalar dependencias del frontend
cd ../frontend
npm install

# Volver al root y ejecutar con Docker
cd ..
docker compose up --build


Luego abre en tu navegador:
http://localhost:3000

🧩 Estructura del proyecto
/backend
    /src
        controllers/
        models/
        routes/
        services/
    server.js

/frontend
    /src
        components/
        pages/
        hooks/
        utils/
    main.jsx

/docker
    nginx.conf

README.md
docker-compose.yml

🧪 Tests
# Backend
cd backend
npm run test

# Frontend
cd ../frontend
npm run test

🤝 Contribuciones

¡Las contribuciones son bienvenidas!
Puedes abrir un issue o enviar un pull request para añadir nuevas funciones, mejorar el simulador económico o optimizar la experiencia de usuario.

📄 Licencia

Proyecto ficticio bajo licencia MIT.
