ARTICULOS:
Crear un registro
POST (http://localhost:3036/articulos/)
EJ:
body:
{
  "modelo": "83",
  "color_id": 3,
  "categorie": "zapatillas",
  "status": "active"
}
Actualizar por id
PUT (http://localhost:3036/articulos/id)
EJ:
(http://localhost:3036/articulos/2)
{
  "modelo": "91",
  "color_id": 5,
  "categorie": "sandalias",
  "status": "active"
}
Leer un registro por ID
GET (http://localhost:3036/articulos/id)
EJ:
(http://localhost:3036/articulos/1)
DEVUELVE:
[
  {
    "id": 1,
    "modelo": "83",
    "color_id": 3,
    "categorie": "zapatillas",
    "status": "active",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  }
]
Leer todos los registros
GET (http://localhost:3036/articulos/)
DEVUELVE:
[
  {
    "id": 1,
    "modelo": "83",
    "color_id": 3,
    "categorie": "zapatillas",
    "status": "active",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  },
    {
    "id": 2,
    "modelo": "91",
    "color_id": 5,
    "categorie": "sandalias",
    "status": "active",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  },
]
Eliminar un registro por ID
DELETE (http://localhost:3036/articulos/id)
EJ: (http://localhost:3036/articulos/2)


AUTORES:
Crear un autor
POST (http://localhost:3036/autores/)
EJ:
body:
{
  "name": "Javier",
  "surname": "Aguirre"
}
Leer todos los autores
GET (http://localhost:3036/autores/)
DEVUELVE:
[
  {
    "id": 1,
    "name": "Javier",
    "surname": "Aguirre",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  },
    {
    "id": 2,
    "name": "Javi",
    "surname": "H",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  }
]
Leer un autor por id
GET (http://localhost:3036/autores/id)
EJ:(http://localhost:3036/autores/1)
DEVUELVE:
[
  {
    "id": 1,
    "name": "Javier",
    "surname": "Aguirre",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  },
]
Eliminar un autor por ID
DELETE (http://localhost:3036/autores/id)
EJ: (http://localhost:3036/autores/2)


COLORES:
Crear un color
POST (http://localhost:3036/colores/)
EJ:
body:
{
  "nombre": "Negro"
}
Leer todos los colores
GET (http://localhost:3036/colores/)
DEVUELVE:
[
  {
    "id": 1,
    "nombre": "Negro",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  },
  {
    "id": 2,
    "nombre": "Blanco",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  }
]
Leer un color por id
GET (http://localhost:3036/colores/id)
EJ:(http://localhost:3036/colores/1)
DEVUELVE:
[
  {
    "id": 1,
    "nombre": "Negro",
    "createdAt": "2024-11-24",
    "updatedAt": "2024-11-24"
  }
]
Eliminar un color por ID
DELETE (http://localhost:3036/colores/id)
EJ:(http://localhost:3036/colores/1)
