# Refaccionaria de Motos - El Jony 🛵🔧

Este proyecto es una aplicación web para la administración y venta de refacciones para motocicletas. Está diseñada para facilitar la gestión de productos, pedidos, inventario y clientes en una refaccionaria.

---

## 📌 Descripción del proyecto

**"El Jony"** permite:

- Registrar y actualizar productos en inventario.
- Gestionar ventas y pedidos.
- Consultar disponibilidad de refacciones.
- Usar una API para conectar con apps externas (como una app móvil o punto de venta).

---

## 🖼️ Capturas de pantalla

### 🧾 Panel de productos

![Panel de productos](./screenshots/productos.png)

### 📦 Registro de refacciones

![Formulario de registro](./screenshots/registro.png)

---

## 💻 Tecnologías utilizadas

- **HTML5 / CSS3 / JavaScript**
- **Node.js + Express.js** (Servidor)
- **MongoDB** (Base de datos)
- **Postman** (para pruebas de la API)
- **Git** (control de versiones)

---

## ⚙️ Instrucciones de instalación

1. Clona este repositorio:

```bash
git clone https://github.com/tu-usuario/refaccionaria-el-jony.git
cd refaccionaria-el-jony
```

2. Instala las dependencias:

```bash
npm install
```

3. Crea el archivo `.env` con las siguientes variables:

```env
PORT=3000
DB_URL=mongodb://localhost:27017/el_jony
```

---

## ▶️ Cómo ejecutar la aplicación

Para iniciar la aplicación en modo desarrollo:

```bash
npm run dev
```

Para iniciar en modo producción:

```bash
npm start
```

Accede a la app en:  
[http://localhost:3000](http://localhost:3000)

---

## 📡 Ejemplos de uso de la API

### Obtener todas las refacciones

```http
GET /api/refacciones
```

### Agregar nueva refacción

```http
POST /api/refacciones
Content-Type: application/json

{
  "nombre": "Pastillas de freno",
  "precio": 180,
  "stock": 30
}
```

---

## ☁️ Despliegue en servidor (opcional)

Puedes subir esta app a un servidor como:

- **Render**
- **Railway**
- **Heroku**
- **Vercel (si es front-end separado)**

### Ejemplo de despliegue con Render:

1. Subir el repositorio a GitHub.
2. Entrar a [https://render.com](https://render.com).
3. Crear un nuevo servicio web conectado a tu repo.
4. Configurar el entorno:
   - `PORT = 3000`
   - `DB_URL = tu_url_de_mongodb_en_la_nube`
5. Click en "Deploy".

---

## ✍️ Autor

**Brandon Uriel Mejía Villafranca**  
Estudiante de Desarrollo de Software Multiplataforma  
Universidad Tecnológica Fidel Velázquez

---

## 🪪 Licencia

Este proyecto está bajo la licencia MIT.