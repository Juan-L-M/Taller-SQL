**Análisis de Base de Datos de Empleados con SQL**

Descripción General
Este proyecto contiene una serie de consultas SQL para analizar una base de datos de empleados. La base de datos incluye información sobre empleados, departamentos, salarios y roles dentro de una empresa.
Estructura de la Base de Datos
La base de datos está compuesta por varias tablas:

employees: Contiene información de empleados (emp_no, first_name, last_name, gender)
departments: Contiene información de departamentos (dept_no, dept_name)
salaries: Contiene información de salarios
dept_emp: Vincula empleados con departamentos

Análisis Realizados
Estadísticas Básicas

Número total de empleados: 300.024
Número de departamentos: 9
Distribución por género:

Empleadas mujeres: 120.051
Empleados hombres: 179.973



Análisis de Salarios

Salario promedio: $63.810,74
Salario más alto: $158.220
Salario más bajo: $38.623

Exploración de Datos

Listado de departamentos (primeros 5):

Servicio al Cliente (d009)
Desarrollo (d005)
Finanzas (d002)
Recursos Humanos (d003)
Marketing (d001)



Información de Empleados

Empleado con salario más alto: Georgi Facello
Empleado con salario más bajo: Georgi Facello
Primeros 100 empleados listados alfabéticamente por apellido (muestra incluida en los datos)

Consultas Incluidas

Exploración básica de departamentos
Conteo de empleados
Conteo de departamentos
Cálculo de salario promedio
Identificación de salarios máximos y mínimos
Conteo de empleados por género
Listado alfabético de empleados
Identificación de empleados por salario con información departamental

Notas

Todas las consultas utilizan operaciones JOIN apropiadas para conectar tablas relacionadas
Las consultas demuestran el uso de:

Funciones de agregación (COUNT, AVG, MAX, MIN)
Cláusulas ORDER BY
Cláusulas LIMIT
Operaciones JOIN
Condiciones WHERE
Alias de tablas
