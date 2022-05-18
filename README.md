## Uso de este repositorio

### Pasos

- Clonar repositorio: `git clone https://github.com/Moya1986/entregafinalreact.git`

- Ejecutar npm para instalar las dependencias: `npm i`

- Ejecutar: `npm start`


### Detalles del proyecto

- Se utiliza Bootstrap para el diseño.

- Se utiliza Firebase, Firestore. Hay que crear un usuario y luego un proyecto. Clikear en la ruedita de configuración, luego en configuración del proyecto, allí encontraremos el código SDK necesario para inicializar firebase en nuestro proyecto. Es importante crear el .env para que esta información no quede en el repositorio.

- El proyecto permite tener la interface de un Ecommerce, con productos y un carrito de compras. Al seleccionar productos se puede ver un detalle de los mismos y, a la vez, seleccionar la cantidad a comprar. Luego se genera una órden de compra que queda guardada en firebase y entrega un código de compra al usuario. No está configurado el backend del form para que le llegue un mail al usuario con la compra.

#### Página inicial

https://raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/home.png

#### Category/Camisetas

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/seccion_camisetas.png

#### ItemDetail con el counter

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/Item.png
  
#### Cart

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/cart_with_products.png

#### Firebase Products

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/products_firebase.png

#### Form Error

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/cart_form_error.png

#### Compra exitosa

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/compra.png

#### Orden creada en firestore luego de la compra

https:/raw.githubusercontent.com/Moya1986/entregafinalreact/main/public/orders_firebase.png




