## Endpoints
- POST /api/products
- GET /api/products
- GET /api/products/{id}
- PUT /api/products/{id}
- DELETE /api/products/{id}
- GET /api/products/{id}/availability?count=n
- GET /api/products/sorted/by-price[?native=true]

# -------------------
# Database connection
# -------------------
quarkus.datasource.db-kind=mysql
quarkus.datasource.username=root
quarkus.datasource.password=root

# Replace with your MySQL host, port, and database name
quarkus.datasource.jdbc.url=jdbc:mysql://localhost:3306/products?useSSL=false&serverTimezone=UTC

