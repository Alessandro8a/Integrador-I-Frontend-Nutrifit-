# NutriFit Frontend - Aplicación Web en React

## 🥗 Descripción

**NutriFit** es una aplicación web interactiva que permite a los usuarios planificar comidas saludables adaptadas a su presupuesto semanal o mensual. Este repositorio contiene el **frontend desarrollado en React**, encargado de proporcionar una experiencia de usuario intuitiva y conectarse con el backend (Spring Boot) mediante una API REST.

## 🎯 Funcionalidades

- Registro e inicio de sesión de usuarios.
- Registro de presupuesto semanal para alimentos.
- Generador de planes de comida personalizados.
- Visualización y selección de recetas saludables.
- Seguimiento en tiempo real del gasto vs. presupuesto.
- Historial de planes de comidas y presupuestos anteriores.
- Cálculo de IMC con recomendaciones.
- Exportación de planes e historial en PDF.
- Responsive design para dispositivos móviles.

## 🧰 Tecnologías Utilizadas

- React 18+
- React Router DOM
- Axios
- TailwindCSS / CSS Modules
- React Hook Form + Yup (validaciones)
- jsPDF / html2canvas (para generación de PDF)
- Context API (para manejo de sesión)
- Vite (para desarrollo y build)

## ⚙️ Instalación y Ejecución

Instala las dependencias:

npm install

Crea un archivo .env en la raíz del proyecto con la URL de tu backend:

npm run dev

Accede desde tu navegador en:

http://localhost:5173

📄 Principales Vistas
- Inicio: Noticias de nutrición, tips, videos saludables, IMC y FAQ.

- Login / Registro: Creación y acceso a cuentas de usuario.

- Dashboard: Panel principal con resumen de estado, acceso a funcionalidades clave.

- Planificador: Ingreso de presupuesto, selección de recetas por día, resumen del plan y generación de PDF.

- Historial: Listado de presupuestos pasados, fechas y exportación total en PDF.

📋 Consideraciones
Asegúrate de tener el backend corriendo en paralelo (nutrifit-backend) para el correcto funcionamiento.

Habilita CORS en el backend si se usa desde un host diferente.

Puedes personalizar los colores y estilos desde tailwind.config.js si estás usando Tailwind.
