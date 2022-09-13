# consultas1_sql

#CONSULTAS SQL

![tabla usuario](img/tabla_usuario.png "tabla usuario")

1. Para visualizar toda la informacion que contiene la tabla `usuario` se puede incluir con la inclusion SELCET el caracter "*" o cada uno de los campos de la tabla
`select * from usuario`

![](img/img1.png "consulta 1")

2. Visualizar solamente la identificacion del usuario.

`select Identification from usuario`

![](img/img2.png "consulta2")

3. Se desea obtener los registros cuya identidad sea mayores o iguales a 150, se utiliza la clausula where que especifica los condiciones que deben reunir los registros que se vam a seleccionar.

`SELECT * FROM usuario WHERE identification>='150'`

![Consulta3](img/img3.png "consulta3")