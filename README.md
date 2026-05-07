
````md
# API con Next.js

Este proyecto es una API sencilla construida con Next.js que proporciona tres endpoints:

- GET /api/users → Devuelve una lista de usuarios en formato JSON.
- GET /api/products → Devuelve una lista de productos en formato JSON.
- POST /api/product → Permite agregar un producto enviando un JSON con name y price.

Además, la API está documentada con Swagger para facilitar su uso y pruebas interactivas.

---

## 📦 Instalación

Clonar el repositorio:

```bash
git clone https://github.com/Yvesdefaria/mi-app-swagger.git
cd mi-app-swagger
````

Instalar dependencias:

```bash
npm install
```

---

## 🚀 Ejecución en local

Para iniciar el servidor en desarrollo:

```bash
npm run dev
```

Esto iniciará un servidor en:

[http://localhost:3000](http://localhost:3000)

---

## 🔗 Endpoints disponibles

### 👤 Usuarios

GET [http://localhost:3000/api/users](http://localhost:3000/api/users)
Devuelve una lista de usuarios en formato JSON.

---

### 📦 Productos

GET [http://localhost:3000/api/products](http://localhost:3000/api/products)
Devuelve una lista de productos en formato JSON.

---

### ➕ Subir producto

POST [http://localhost:3000/api/product](http://localhost:3000/api/product)

Body JSON:

```json
{
  "name": "producto1",
  "price": 5.5
}
```

---

## 📘 Documentación Swagger

La API cuenta con documentación interactiva generada con Swagger.

Accede aquí:

[http://localhost:3000/api-docs](http://localhost:3000/api-docs)

Desde esta interfaz puedes:

* Ver todos los endpoints disponibles
* Probar GET y POST directamente desde el navegador
* Ver respuestas en tiempo real

---

## 🌍 Despliegue

Puedes desplegar la API en Vercel con:

```bash
npm run build
vercel deploy
```

O subirlo a cualquier servidor compatible con Next.js.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo y modificarlo libremente.

---

## 🚀 Autor

Proyecto realizado con Next.js + Swagger para práctica de APIs REST.

```

---
