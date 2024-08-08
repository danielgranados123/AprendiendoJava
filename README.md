----Script de la base de datos----

CREATE TABLE tbProductos(
    uuid_producto varchar2(100) primary key,
    nombre varchar2(100),
    precio number(5,2),
    categoria varchar2(100)
);

drop table tbProductos cascade constraints;
