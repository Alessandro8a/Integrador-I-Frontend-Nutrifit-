### **NutriFit Frontend – Aplicación Web desarrollada en React**

🥗 **Descripción**

NutriFit es una plataforma web dinámica que ayuda a los usuarios a organizar planes de alimentación saludable ajustados a un presupuesto semanal o mensual. Este repositorio corresponde al **frontend**, implementado con **React**, y se encarga de ofrecer una interfaz amigable y de comunicarse con el backend en **Spring Boot** a través de una **API REST**.

🎯 **Características principales**

* Registro y autenticación de usuarios.
* Gestión de presupuesto alimenticio semanal.
* Generación automática de planes de comidas personalizados.
* Exploración y elección de recetas saludables.
* Monitoreo en tiempo real del gasto frente al presupuesto disponible.
* Consulta del historial de planes de comidas y presupuestos anteriores.
* Cálculo del IMC con sugerencias nutricionales.
* Exportación de planes e historiales en formato PDF.
* Diseño adaptable a dispositivos móviles (responsive).

🧰 **Tecnologías empleadas**

* React 18 o superior
* React Router DOM
* Axios
* TailwindCSS / CSS Modules
* React Hook Form + Yup para validaciones
* jsPDF / html2canvas para exportación en PDF
* Context API para la gestión de sesiones
* Vite para entorno de desarrollo y compilación

⚙️ **Instalación y ejecución**

1. Instala las dependencias del proyecto:

   ```bash
   npm install
   ```
2. Crea un archivo `.env` en la raíz del proyecto con la URL del backend.
3. Inicia la aplicación:

   ```bash
   npm run dev
   ```
4. Accede desde el navegador en:

   ```
   http://localhost:5173
   ```

📄 **Vistas principales**

* **Inicio:** Contenido informativo sobre nutrición, consejos, videos, cálculo de IMC y preguntas frecuentes.
* **Login / Registro:** Creación y acceso a cuentas de usuario.
* **Dashboard:** Panel general con un resumen del estado y accesos rápidos a las funcionalidades.
* **Planificador:** Carga de presupuesto, selección diaria de recetas, resumen del plan y exportación en PDF.
* **Historial:** Visualización de presupuestos anteriores, fechas y descarga del historial completo en PDF.

📋 **Consideraciones**

* Es necesario ejecutar el backend (**nutrifit-backend**) simultáneamente para un funcionamiento correcto.
* Asegúrate de habilitar **CORS** en el backend si el frontend se consume desde un dominio distinto.
* Los estilos y colores pueden personalizarse desde `tailwind.config.js` en caso de usar TailwindCSS.
