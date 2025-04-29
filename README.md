# 🦄 Unicorn CRUD con React + PrimeReact

## 📝 Descripción del Proyecto

Este proyecto es una aplicación CRUD (Crear, Leer, Actualizar, Eliminar) para gestionar una lista de unicornios. Está desarrollada utilizando React, PrimeReact y Vite, y se conecta a una API REST externa proporcionada por [crudcrud.com](https://crudcrud.com/) para el almacenamiento temporal de datos.

## 🚀 Tecnologías Utilizadas

- ⚛️ React + Vite
- 🎨 PrimeReact
- 🧭 React Router DOM
- 🌐 API externa: [crudcrud.com](https://crudcrud.com/)
- 🪝 Hooks de React: `useState`, `useEffect`

## 🦄 Estructura del Objeto Unicornio

```json
{
  "name": "Twilight Sparkle",
  "data": {
    "color": "purple",
    "age": 100,
    "power": "Magic"
  }
}
```

## ⚙️ Funcionalidades CRUD

- **Create**: Agrega nuevos unicornios mediante un formulario.
- **Read**: Muestra la lista de unicornios en una tabla.
- **Update**: Permite editar los detalles de un unicornio seleccionado.
- **Delete**: Elimina unicornios seleccionados de la lista.

## 🧭 Navegación con Rutas

La aplicación utiliza `react-router-dom` para manejar las rutas:

- `/unicornios` → Vista principal del módulo de unicornios.

## 🛠️ Instalación y Ejecución

Sigue estos pasos para instalar y ejecutar el proyecto localmente:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/SantiBz05/ContextApi-CRUD-Unicorns.git
   ```

2. **Accede al directorio del proyecto:**

   ```bash
   cd ContextApi-CRUD-Unicorns
   ```

3. **Instala las dependencias:**

   ```bash
   npm install
   ```

4. **Obtén tu API Key de crudcrud.com:**

   - Visita [crudcrud.com](https://crudcrud.com/) y copia la URL de tu API personal.
   - Reemplaza la URL en el archivo correspondiente del proyecto (por ejemplo, en `UnicornsContainer.jsx`) con tu nueva API Key.

5. **Inicia el servidor de desarrollo:**

   ```bash
   npm run dev
   ```

   La aplicación estará disponible en `http://localhost:5173`.


