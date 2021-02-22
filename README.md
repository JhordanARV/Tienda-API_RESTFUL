# Tienda-API_RESTFUL
Tienda virtual

# INSTALL

npm install

backend> node index.js

# CREAR VENTA

POST http://localhost:3000/sales/
{
    "clientId": "603330a755fd3b1c941fbaad", <-- ID cliente
    "details": {
       "bookId": "603339a655627a105c97a3b1", <-- ID libro
        "name": "Libro",
        "unitValue": 2,
        "quantity": 1
    },
    "total": 2
}