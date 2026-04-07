# 🐳 Proyecto Docker - sem04

## 📌 Descripción

Este proyecto consiste en una aplicación web simple desarrollada con Flask, ejecutada dentro de un contenedor Docker y desplegada en un servidor EC2.

---

## ⚙️ Tecnologías usadas

* Python 3.11
* Flask
* Docker
* AWS EC2

---

## 🚀 Cómo ejecutar el proyecto

### 1. Construir la imagen

```bash
docker build -t mi-app .
```

### 2. Ejecutar el contenedor

```bash
docker run -d -p 5000:5000 mi-app
```

---

## 🌐 Acceso

Abrir en el navegador:

```
http://TU-IP:5000
```

---

## 📁 Estructura del proyecto

```
sem04/
 ├── app.py
 ├── requirements.txt
 ├── Dockerfile
 ├── Dockerfile.optimizado
 ├── Dockerfile.multistage
 └── .dockerignore
```

---

## 👤 Autor

* Anderson Miguel Ninahuaman Yuto
  
