# 🐾 Salva-Mascotas  
### ¿Dónde estás, Peludito?

🌐 **Sitio web oficial:**  
👉 https://dondeestaspeludito.com/

---

## 📌 Descripción General

**Salva-Mascotas** es una plataforma web desarrollada como proyecto integrador que permite reportar mascotas perdidas y encontradas, visualizar reportes cercanos mediante geolocalización y realizar coincidencias automáticas utilizando inteligencia artificial basada en reconocimiento de imágenes.

El objetivo principal del sistema es facilitar el reencuentro entre mascotas extraviadas y sus dueños, centralizando la información en una plataforma confiable, moderna y accesible desde cualquier dispositivo.

---

## 🎯 Objetivos del Proyecto

- Desarrollar un sistema web **full-stack funcional**
- Integrar completamente frontend y backend mediante **API REST**
- Implementar operaciones **CRUD completas**
- Utilizar **geolocalización** para mostrar mascotas cercanas
- Implementar **inteligencia artificial** para coincidencia de mascotas por imagen
- Demostrar competencias técnicas en desarrollo web moderno

---

## 🧱 Arquitectura del Sistema

El sistema utiliza una **arquitectura de N-capas (MVC)**:

- **Frontend (Presentación):** React + Vite + TypeScript  
- **Backend (Aplicación):** Node.js + Express  
- **Base de Datos (Persistencia):** PostgreSQL (Supabase)  
- **Almacenamiento:** Supabase Storage  
- **IA:** OpenAI Vision (comparación de imágenes)  
- **Integración:** API REST  

---

## 🧩 Módulos del Sistema

### 🔐 Usuarios / Autenticación
- Estructura preparada para autenticación
- Asociación de reportes con usuarios

### 🐶 Mascotas Perdidas
- Registro de mascotas extraviadas
- Información general, descripción y fotografía
- Ubicación GPS automática

### 🐾 Mascotas Encontradas
- Registro de mascotas encontradas
- Geolocalización del hallazgo
- Fotografías para comparación

### 🗺️ Geolocalización
- Obtención automática de latitud y longitud
- Visualización de mascotas cercanas
- Filtros por estado y características

### 🤖 Coincidencias por Inteligencia Artificial
- Comparación automática de imágenes
- Cálculo de porcentaje de similitud (0–1)
- Registro de coincidencias en base de datos

---

## 🔄 Operaciones CRUD

Cada módulo implementa operaciones CRUD completas:

- **Create:** Alta de reportes
- **Read:** Consulta de información
- **Update:** Modificación de reportes
- **Delete:** Eliminación de registros

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- React
- Vite
- TypeScript
- Tailwind CSS
- Fetch API
- Geolocation API
- Lucide Icons

### Backend
- Node.js
- Express
- Multer (manejo de imágenes)
- Supabase SDK
- OpenAI API (Vision)

### Base de Datos
- PostgreSQL
- Supabase
- Índices geoespaciales
- Vistas y triggers

---

## 🚀 Uso del Sistema

1. Acceder al sitio web:
   👉 https://dondeestaspeludito.com/

2. Reportar una mascota perdida o encontrada
3. Permitir acceso a la ubicación
4. Visualizar mascotas cercanas
5. En caso de mascota encontrada, el sistema ejecuta automáticamente la IA
6. Se generan coincidencias con mascotas perdidas registradas

---

## 📦 Instalación Local (opcional)

### Backend
```bash
npm install
npm run dev
