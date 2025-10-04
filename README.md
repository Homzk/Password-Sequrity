# Evaluador de Fortaleza de Contraseñas 🔒

Una aplicación web moderna que evalúa la fortaleza de contraseñas utilizando algoritmos de Machine Learning. Desarrollada con React, TypeScript y Python.

## 🚀 Características

- Evaluación en tiempo real de la fortaleza de contraseñas
- Análisis de seguridad potenciado por Machine Learning
- Interfaz de usuario moderna y responsiva con Tailwind CSS
- Desarrollo con seguridad de tipos usando TypeScript
- API segura en el backend con Python

## 🛠️ Tecnologías Utilizadas

### Frontend
- React 18
- TypeScript
- Tailwind CSS
- Vite (Herramienta de Construcción)

### Backend
- Python (FastAPI/Flask - Por definir)
- Machine Learning (scikit-learn/TensorFlow - Por definir)

## 🚀 Comenzando

### Requisitos Previos

- Node.js (v16+)
- Python (3.8+)
- npm o yarn

### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/evaluador-fortaleza-contrasenas.git
   cd evaluador-fortaleza-contrasenas
   ```

2. **Instalar dependencias del frontend**
   ```bash
   cd frontend
   npm install
   # o
   yarn install
   ```

3. **Configurar el backend**
   ```bash
   cd ../backend
   python -m venv venv
   source venv/bin/activate  # En Windows: .\venv\Scripts\activate
   pip install -r requirements.txt
   ```

### Ejecutando la Aplicación

1. **Iniciar el frontend**
   ```bash
   cd frontend
   npm run dev
   ```

2. **Iniciar el backend**
   ```bash
   cd backend
   python app.py
   ```

La aplicación estará disponible en `http://localhost:3000`

## 📂 Estructura del Proyecto

```
evaluador-fortaleza-contrasenas/
├── frontend/               # Aplicación React frontend
│   ├── src/
│   │   ├── components/     # Componentes UI reutilizables
│   │   ├── pages/          # Páginas de la aplicación
│   │   ├── services/       # Servicios de API
│   │   └── App.tsx         # Componente principal
│   └── package.json
│
├── backend/                # Backend en Python
│   ├── app/                # Código de la aplicación
│   │   ├── models/         # Modelos de ML
│   │   ├── routes/         # Rutas de la API
│   │   └── services/       # Lógica de negocio
│   ├── requirements.txt    # Dependencias de Python
│   └── app.py             # Punto de entrada
│
└── README.md
```

## 🤝 Cómo Contribuir

1. Haz un fork del repositorio
2. Crea tu rama de características (`git checkout -b feature/NuevaCaracteristica`)
3. Haz commit de tus cambios (`git commit -m 'Añadir NuevaCaracteristica'`)
4. Haz push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Reconocimientos

- [Vite](https://vitejs.dev/) - Herramienta Frontend de Próxima Generación
- [Tailwind CSS](https://tailwindcss.com/) - Un framework CSS utility-first
- [FastAPI](https://fastapi.tiangolo.com/) - Framework web moderno y rápido para construir APIs
