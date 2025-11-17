# Calculadora-de-Presupuesto-Mensual
Una calculadora de presupuesto mensual es una herramienta que ayuda a las personas a administrar sus finanzas personales. Básicamente, permite registrar los ingresos y gastos durante un mes para calcular el balance financiero, ayudando a determinar si hay un superávit (sobrante) o un déficit (falta de dinero).

## Requerimientos Funcionales
|ID|Tipo|Descripcion|
|-|-|---------|
|RF1|Ingreso de datos|El sistema debe permitir al usuario ingresar los gastos e ingresos mensuales|
|RF2|Calculo automatico|El sistema debe calcular automáticamente el saldo disponible|
|RF3|Clasificacion|El sistema debe permitir clasificar los datos por categoría|
|RF4|Visualizacion|El sistema debe mostrar un resumen general del presupuesto indicando el total de ingresos, total de gastos y sueldo final|
|RF5|Alertas|El sistema debe mostrar una alerta o notificación si los gastos superan los ingresos|
|RF6|Historial|El sistema debe permitir consultar los presupuestos anteriores|
|RF7|Edicion y eliminacion|El sistema debe permitir consultar los ingresos anteriores|
|RF8|Exportacion|El sistema debe permitir exportar el presupuesto mensual en formato como PDF o Excel|

## Requerimientos no Funcionales
|ID|Tipo|Descripcion|
|-|-|--------|
|RNF1|Usabilidad|La interfaz debe ser intuitiva, fácil de usar y comprensible para cualquier usuario sin conocimientos técnicos|
|RNF2|Compatibilidad|La aplicación debe ser compatible con computadoras y dispositivos móviles|
|RNF3|Portabilidad|El sistema debe poder ejecutarse en diferentes sistemas operativos|
|RNF4|Accesibilidad|La aplicación debe cumplir con estándares básicos de accesibilidad|
|RNF5|Privacidad|La información personal y financiera del usuario no debe compartirse con terceros|

## Tabla de Prueba
|N°|Requerimiento asociado|Datos de entrada|Resultado esperado|Resultado obtenido/Validacion|
|-|-|-|-|-|
|1.|Calcular total de ingresos mensuales|Ingresos: Saldo:890;<br>Otros:200|Total Ingresos:<br>1090|Total Ingresos:<br>1090|
|2.|Calcular todos los gastos mensuales|Gastos: Alquiler:300;<br>Comida:180|Total Gastos:<br>480|Total Gastos:<br>480|
|3.|Calcular el presupuesto mensual|Ingresos: 1090<br>Gastos:480|Total Saldo:<br>610|Total Saldo:<br>610|

## Propuesta de Mantenimiento

1.-Mantenimiento Correctivo

Este tiene como objetivo solucionar o detectar errores durante el uso de la calculadora.

Casos a considerar:

1.-Correcion de errores en formulas de calculo.

2.-Correcion de errores de validacion en la interfaz.

3.-Ajuste de errores de interfaz como mala visualizacion de pantallas pequeñas.

Acciones que se pueden tomar para corregir esto:

1.-Revisar y corregir funciones de calculo.

2.-Implementar manejo de excepciones para entradas validas.

3.-Ejecucion de pruebas unitarias sobre los modulos afectados.

# ¿Investigacion sobre el uso de Markdown?
## ¿Que es Markdown y porque se utiliza en proyectos de software?
+ Es un lenguaje de marcado ligero que permite formatear texto plano de forma sencilla utilizando caracteres como #, * y _ para crear titulos, negritas, cursivas, listas, etc. Su diseño prioriza la legibilidad del texto, tanto en su forma de escritura como de lectura, y puede convertirse facilmente a HTMLy otros formatos.
+ 

