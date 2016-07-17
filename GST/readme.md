#GST#

##UTILIDADES##

* Clientes
* Pedidos de clientes
* Almacén
* Taller
* Facturación
* Control de costes

###TABLAS###

+ Clientes
    + Nombre
    + Direccion
    + CIF
    + Telefono
    + Email
    + Persona de contacto
    + IVA (bool)
    + Formas de pago
    + IBAN
    + SWIFT
    + Courier number
+ Proveedores
    + Nombre
    + Direccion
    + CIF
    + Telefono
    + Email
    + Persona de contacto
    + IVA (bool)
    + Forma de pago
    + IBAN
    + SWIFT
    + Courier number
+ Trabajos (tipo)
    + Nombre
+ Materias
    + Descriptivo
    + Nombre
    + Proveedor predef.
+ Piezas-Trabajos
	+ Id
	+ Pieza
    + Tareas
    + Coste
+ Piezas - Materias
	+ Id
	+ Pieza
    + Materia
    + Cantidad
+ Tareas
    + Pieza
    + Trabajo
    + Trabajador
    + Cantidad
+ Empleados
+ Piezas

###FUNCIONALIDADES###

