
PRUEBA DE PRÁCTICA


1.	Crear entorno virtual env.
2.	Clonar repositorio.
3.	Realizar migración de tablas a la base de datos.
4.	En la carpeta aplicaciones crear app con el nombre mod.
5.	Crear modelos

Modelo Cliente
nombre; tipo string
direccion; tipo string
estado; tipo boolean
create_by; tipo date
update_by; tipo date

Modelo Articulo
nombre; tipo string
stockInicial; tipo int
precio; tipo int
estado; tipo boolean
create_by; tipo date
update_by; tipo date

Modelo Pedido
cliente = ForeignKey
articulo = ForeignKey
cantidad; tipo int
estado; tipo boolean
create_by; tipo date
update_by; tipo date
	
6.	Crear los formularios necesarios en forms.py. 
7.	Vistas para listar, editar y eliminar (realizar eliminación lógica).
8.  Al Editar los pedidos, se debe actualizar el stock del producto.
9.  Posibilidad de ingresar varios productos en una sola vista.
