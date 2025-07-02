# 🧠 Actividad: "Mi colección de libros favoritos"

## 🎯 Descripción

Crea una aplicación en React que muestre una galería de libros usando tarjetas. Los datos de los libros deben venir de un archivo JSON simulado (como si fuera una API). Cada tarjeta debe mostrar:

- Título del libro  
- Autor  
- Imagen de portada (puede ser la misma para todos)  
- Lista de géneros

---

## 🧠 Objetivos de aprendizaje

- Practicar la descomposición en componentes.
- Utilizar `props` para pasar datos entre componentes.
- Implementar `useEffect` para simular carga de datos desde un archivo JSON.
- Usar `useState` para manejar estado local.
- Aplicar Bootstrap para el diseño (cards, grid, layout).

---

## 📁 Estructura sugerida

```
src/
├── components/
│   ├── Navbar.jsx
│   ├── LibroCard.jsx
│   └── Libros.jsx
├── data/
│   └── libros.json
├── App.jsx
└── main.jsx
```

---

## 📘 Contenido de `libros.json` (ejemplo)

```json
[
  {
    "titulo": "1984",
    "autor": "George Orwell",
    "imagen": "portada-default.jpg",
    "generos": ["Distopía", "Ciencia ficción"]
  },
  {
    "titulo": "Cien años de soledad",
    "autor": "Gabriel García Márquez",
    "imagen": "portada-default.jpg",
    "generos": ["Realismo mágico", "Literatura latinoamericana"]
  }
]
```

---

## ✅ Requisitos mínimos

- [ ] Mostrar al menos 6 libros desde un JSON.
- [ ] Dividir en al menos 2 componentes: `LibroCard` y `Libros`.
- [ ] Usar `useEffect` para cargar los datos del JSON.
- [ ] Usar `props` para pasar los datos a las tarjetas.
- [ ] Aplicar Bootstrap para mostrar las tarjetas en una grilla responsiva.

---

## 🌟 Extra (opcional)

- [ ] Agregar una barra de navegación.
- [ ] Mostrar cantidad total de libros cargados.
- [ ] Agregar un botón en cada tarjeta que abra el link a más información (por ejemplo, una página de Wikipedia del autor).

---
# react-libros
