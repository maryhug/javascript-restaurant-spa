<div align="center">

  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/JSON%20Server-000000?style=for-the-badge&logo=json&logoColor=white" />

  <h1>Restaurant SPA</h1>
  <p>Aplicación de página única (SPA) para gestión de restaurante, construida con JavaScript vanilla y Vite. Incluye autenticación, roles de usuario y router propio sin frameworks.</p>

</div>

---

## Vistas

| Vista | Descripción |
|---|---|
| `LoginView` | Autenticación de usuarios |
| `MenuView` | Carta del restaurante |
| `OrdersView` | Gestión de pedidos |
| `AdminView` | Panel de administración |
| `ProfileView` | Perfil del usuario |

## Arquitectura
```
src/
├── main.js # Punto de entrada
├── router/ # Enrutador SPA propio
├── views/ # Vistas de la aplicación
├── components/ # Componentes reutilizables
├── services/ # Llamadas a JSON Server
├── state/ # Estado global + db.json
└── utils/ # Funciones auxiliares
```


## Tecnologías

- JavaScript vanilla sin frameworks
- Vite como bundler y servidor de desarrollo
- JSON Server como API REST simulada

## Instalación y uso

```bash
git clone https://github.com/maryhug/restaurant-spa.git
cd restaurant-spa
npm install
```

Ejecutar en dos terminales:

```bash
# Terminal 1 — API REST
npm run server

# Terminal 2 — Frontend
npm run dev
```

## Imagen de referencia 

![img_1.png](img_1.png)
![img.png](img.png)
