# Triggers
Hecha por Brayan Steven López

Para dar Respuesta al Foro:Aplicación Trigers, se creo un nuevo triger llamado NewFactura, el cual funcionara cada vez que se inserte una nueva factura y mantenga el inventario actualizado.

![image](https://github.com/user-attachments/assets/e0efedb4-4d07-4396-8f18-5b4771cc0631)

Esto lo hara llamando a un procedimiento almacenado llamado ActualizarInventario al cual se le enviara como parametro de entrada el IdProducto nuevo como la cantidad de la nueva factura, con estos datos lo que hara sera Actualizar la cantidad de ese IdProdcuto tomando la cantidad actual del inventario y restandole la cantidad de la nueva factura.

![image](https://github.com/user-attachments/assets/151d38be-e514-4096-bd74-a7fe8efa0d0d)

como ejemplo podemos ver las tablas inventario, y facturas:

![image](https://github.com/user-attachments/assets/4888ed55-c6c0-4ab0-8d31-b8c108b23ca3)

![image](https://github.com/user-attachments/assets/f24d68fa-39a5-441a-9330-d87c48b0f018)

y ahora ingresaremos una nueva factura en la cual se veran reflejadas las ventas del IdProducto "4" con 120 unidades. 

![image](https://github.com/user-attachments/assets/e17820e8-55c6-41c8-9bcc-a7ba7dc0c650)

Tambien verificaremos que el invetario se halla actualizado: 

![image](https://github.com/user-attachments/assets/b10db503-647d-481b-a843-e6bb5c1590c4)

Como se refeleja en el ejemplo el Triger quedo funcionando correctamente.
