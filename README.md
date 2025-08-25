# 🌳 Tu Bosque SAIA – Módulo Ecológico Gamificado

**Tu Bosque SAIA** es un módulo visual y simbólico que se integra al sistema de gestión documental SAIA® para reflejar el impacto ambiental positivo de los usuarios al digitalizar documentos. Cada hoja ahorrada se traduce en árboles virtuales, métricas ecológicas y logros visuales, motivando el uso sostenible del sistema.

---

## 🎯 Objetivo

Diseñar e implementar una funcionalidad gamificada y no intrusiva que incentive la conciencia ambiental mediante:

- Visualización de un bosque digital personal  
- Medición de hojas ahorradas, árboles salvados, CO₂ evitado, agua y energía ahorradas  
- Sistema de logros y frases motivadoras  
- Integración con estadísticas reales del sistema SAIA

---

## ⚙️ Tecnologías

- **Frontend:**
  - HTML + CSS + JavaScript
  - [Chart.js](https://www.chartjs.org/) – gráficas
  - [GSAP](https://greensock.com/gsap/) o [Lottie](https://lottiefiles.com/) – animaciones
  - [PixiJS](https://pixijs.com/) – visualización del bosque (opcional)

- **Backend:**
  - PHP (estructura MVC)
  - Conexión a base de datos SAIA (modo lectura)
  - Migraciones SQL locales

- **Base de Datos:**
  - MySQL
  - Tablas propias del módulo:
    - `usuarios_bosque`
    - `impacto_ambiental`
    - `arboles_virtuales`
    - `logros_desbloqueados`
    - `configuracion_ecologica`

---

## 📁 Estructura inicial del proyecto

tu-bosque-saia/
├── controllers/
├── models/
├── views/
├── assets/
├── database/
│   └── schema.sql
├── sprints/
│   └── sprint-01.md
├── .env.example
├── .gitignore
└── README.md

---

## 🧪 Requisitos

- PHP 7.4+
- MySQL
- Acceso de solo lectura a la base de datos de SAIA
- Variables de entorno configuradas en un archivo `.env`

---

## 🔧 Instalación rápida

1. Clona el repositorio:

   ```bash
   git clone https://github.com/jwramirezc/mi-bosque.git
   cd mi-bosque


   🗂️ Gestión del desarrollo

El desarrollo se divide en 12 sprints quincenales.
Cada sprint se documenta en la carpeta /sprints/ con:
	•	Objetivos del sprint
	•	Tareas técnicas
	•	Casos de uso relacionados
	•	Avance y pendientes

⸻

📚 Documentación adicional
	•	/sprints/: planificación por sprint
	•	/docs/: diseño de interfaz, fórmulas ecológicas, arquitectura técnica
	•	/database/: scripts de creación de tablas

⸻

🤝 Contribución
	1.	Crea un fork
	2.	Crea una nueva rama: **git checkout -b feature/sprint01-logros**
 	3.	Haz tus cambios y súbelos: git commit -m "Agrega cálculo de logros ecológicos"
  4.	Abre un Pull Request


  🔐 Licencia

Este proyecto hace parte del ecosistema SAIA®
© 2025 CERO K S.A.S. – Todos los derechos reservados.
