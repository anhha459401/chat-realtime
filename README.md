#Backend
Tạo package.json: npm init -y
Cài các thư viện cần thiết:
npm i express cors mongoose dotenv
npm i -D nodemon

Thêm "type": "module", vào package.json
Chỉnh "main": "src/server.js",
"scripts": {
"dev": "nodemon src/server.js",
"start": "node src/server.js"
},

npm run dev
npm i jsonwebtoken bcrypt cookie-parser

Cài postman

Tạo token:
node
require('crypto').randomBytes(64).toString('hex')

#Frontend
npm create vite@latest . // tạo ở thư mục hiện tại
cài các thư viện cần thiết
npm i react-router axios lucide-react tailwindcss @tailwindcss/vite tailwindcss-animate zustand zod react-hook-form @hookform/resolvers sonner

npm i -D @types/node

npx shadcn@latest init
radix vega

npx shadcn@latest add signup-04

backend: npm i swagger-ui-express

npx shadcn@latest add switch badge dialog textarea popover

npm i tailwind-scrollbar

npm i react-infinite-scroll-component

npm i emoji-mart @emoji-mart/data @emoji-mart/react

backend: npm i socket.io

npm i socket.io-client

npx shadcn@latest add tabs

backend: npm i cloudinary multer
