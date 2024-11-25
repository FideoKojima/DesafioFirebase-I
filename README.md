# 🔥 Firebase CRUD App con Vue.js

<div align="center">
  
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)
![Vuex](https://img.shields.io/badge/Vuex-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)

</div>

## 📋 Tabla de Contenidos

- [Descripción](#-descripción)
- [Características](#-características)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación](#-instalación)
- [Configuración](#-configuración)
- [Uso](#-uso)
- [Estructura del Proyecto](#-estructura-del-proyecto)

## 📝 Descripción

Este proyecto es una aplicación CRUD (Create, Read, Update, Delete) desarrollada con Vue.js y Firebase. Permite gestionar usuarios a través de una interfaz intuitiva, realizando operaciones básicas de creación, lectura y eliminación de registros utilizando Firebase como backend.

## ✨ Características

- 📝 Crear nuevos usuarios
- 📖 Listar usuarios existentes
- 🗑️ Eliminar usuarios
- 🔄 Actualización en tiempo real
- 🎯 Gestión de estado con Vuex
- 🔥 Integración con Firebase

## 🛠️ Tecnologías Utilizadas

- Vue.js - Framework JavaScript progresivo
- Vuex - Gestión de estado
- Firebase - Backend y base de datos
- JavaScript ES6+
- HTML5 & CSS3

## ⚙️ Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/FideoKojima/DesafioFirebase-I.git
```

2. Navega al directorio del proyecto:

```bash
cd DesafioFirebase-I
```

3. Instala las dependencias:

```bash
npm install
```

## 🔧 Configuración

1. Crea un proyecto en [Firebase Console](https://console.firebase.google.com/)

2. Obtén las credenciales de tu proyecto Firebase

3. Crea un archivo `.env` en la raíz del proyecto:

```env
VUE_APP_FIREBASE_API_KEY=tu_api_key
VUE_APP_FIREBASE_AUTH_DOMAIN=tu_auth_domain
VUE_APP_FIREBASE_PROJECT_ID=tu_project_id
VUE_APP_FIREBASE_STORAGE_BUCKET=tu_storage_bucket
VUE_APP_FIREBASE_MESSAGING_SENDER_ID=tu_messaging_sender_id
VUE_APP_FIREBASE_APP_ID=tu_app_id
```

4. Actualiza la configuración de Firebase en `src/firebase/config.js`

## 🚀 Uso

1. Inicia el servidor de desarrollo:

```bash
npm run serve
```

2. Abre tu navegador y visita:

```
http://localhost:8080
```

## 📁 Estructura del Proyecto

```
firebase-crud-app/
├── src/
│   ├── components/
│   │   ├── UserForm.vue
│   │   └── UserList.vue
│   ├── store/
│   │   └── index.js
│   ├── firebase/
│   │   └── config.js
│   ├── App.vue
│   └── main.js
├── public/
│   └── index.html
├── .env
├── package.json
└── README.md
```

## 🤝 Contribución

1. Fork el proyecto
2. Crea tu rama de característica (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👥 Autores

- Tu Nombre - [@tuUsuario](https://github.com/tuUsuario)

## 🙏 Agradecimientos

- [Vue.js](https://vuejs.org/)
- [Firebase](https://firebase.google.com/)
- [Vuex](https://vuex.vuejs.org/)

---

<div align="center">
  
⭐️ ¡Si te gustó este proyecto, dale una estrella! ⭐️

</div>
