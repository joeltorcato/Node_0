# 📌 node.js rest api study  
this repository contains a rest api project built with **node.js**, **fastify**, and **postgresql**. i developed this application following a rocketseat tutorial to learn backend development fundamentals and database integration.  

## 📂 what i learned  
through this project, i practiced:  
✅ building a rest api with fastify (fast and lightweight framework)  
✅ crud operations (create, read, update, delete)  
✅ database integration with postgresql (using neon serverless)  
✅ environment variables management with dotenv  
✅ http methods and status codes  
✅ query parameters and route parameters  
✅ deploying to render platform  

## 🚀 project features  
- **create videos:** add new video records with title, description, duration, and channel  
- **list videos:** retrieve all videos or search by title  
- **update videos:** modify existing video information  
- **delete videos:** remove videos from the database  

## 🛠️ tech stack  
- **runtime:** node.js with bun  
- **framework:** fastify  
- **database:** postgresql (neon serverless)  
- **orm:** postgres.js  
- **deployment:** render  

## 🎯 purpose  
this project helped me understand how backend apis work, from route handling to database operations. it's a foundation for building more complex applications.  

after learning **c**, **java**, and **mysql**, i'm now expanding into backend development with **node.js** and real-world api creation!  

## 📎 how to run  
```sh
# install dependencies
npm install

# run development server
npm run dev

# the api will be available at http://localhost:3333
```

## 📡 api endpoints  
```
POST   /videos       → create new video
GET    /videos       → list all videos (optional: ?search=title)
PUT    /videos/:id   → update video by id
DELETE /videos/:id   → delete video by id
```

---

**credits:** project developed following rocketseat's tutorial
