# 🛍️ Tienda Tricolor (Demo)

Sitio web de demostración hecho en **HTML + CSS + JavaScript**, con temática tricolor (rojo/negro/blanco).  
Incluye catálogo de productos, filtros, búsqueda, carrito lateral y un checkout de prueba.

⚠️ **Nota:** Este proyecto es 100% educativo y **no oficial**.

---

## 🚀 Demo en GitHub Pages
El sitio queda publicado en:

https://esmerilin.github.io/mi-tienda

*(reemplazá `TUUSUARIO` por tu usuario de GitHub y `mi-tienda` por el nombre de tu repo).*

---

## 📂 Estructura del proyecto
- `index.html` → contiene toda la tienda en un solo archivo (estructura, estilos y lógica JS).
- `README.md` → este archivo de documentación.

---

## ✨ Funcionalidades
- Catálogo de productos con precios, categorías y descripciones.
- Filtros por categoría, rango de precio y etiquetas.
- Búsqueda en vivo.
- Ordenamiento por precio y calificación.
- Carrito lateral con totales dinámicos y simulación de checkout.

---

## 🔧 Personalización
Podés editar el array `RAW_PRODUCTS` dentro de `index.html` para cambiar:
- **Nombre del producto**
- **Precio**
- **Imagen (URL)**
- **Categoría**
- **Tags**
- **Stock**

Ejemplo de producto:
```js
{ 
  id:'cam-25-h', 
  name:'Camiseta Titular', 
  price:89999, 
  category:'Indumentaria', 
  rating:4.8, 
  stock:20, 
  img:'https://picsum.photos/seed/tricolor1/640/420', 
  tags:['camiseta','rayas'], 
  desc:'Franjas rojas, negras y blancas.' 
}
