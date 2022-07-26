# backend-desafioClase42

Aplicación Backend con un CRUD simple.

Rutas:

GET /api/prod/:id? => Si se inserta ID, se trae el producto especificado, caso contrario se traen todos.
POST /api/prod/ => Insertar nuevo producto. Debe ser un objeto que posea los atributos "title" (string), "price" (number) y "description" (string).
PUT /api/prod/:id => Inserta un producto en el ID especificado, debe poseer los mismos atributos que un nuevo producto.
DELETE /api/prod/:id => Elimina el producto en el ID especificado.
