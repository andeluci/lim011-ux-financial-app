# Aplicación financiera

## Índice

[1. Introducción](#1-introducción)
 
[2. Acerca de la empresa](#2-acerca-de-la-empresa)
 
[3. Objetivos iniciales del proyecto](#3-objetivos-iniciales-del-proyecto)
 
[4. Problemas identificados tanto a nivel de negocio como a nivel de usuario](#4-problemas-identificados-tanto-a-nivel-de-negocio-como-a-nivel-de-usuario)
 
[5. Recomendaciones de próximos pasos para el banco con respecto al app](#5-Recomendaciones-de-próximos-pasos-para-el-banco-con-respecto-al-app)
 
[6. KPI'S, Observaciones y NextSteps](#6-kpis-observaciones-nextsteps)

[7. Links](#6-Links)

***

## 1. Introducción

El banco más importante del país, Banco Pichincha, está planeando lanzar un banco 100% digital bajo otro nombre: "Banqui". Han venido piloteando un app con un número pequeño de usuarios siendo los resultados de este piloto mixtos. Nos presentaron los resultados de este piloto que nos sirvió como data/información para la investigación y posterior rediseño de la aplicación. 

## 2. Acerca de la empresa

El Product Manager nos compartió sus impresiones sobre cómo han estado llevando este producto y también nos brindó diferentes recursos para poder hacer un análisis del mismo. Algunos de sus comentarios fueron:

>Los usuarios que anteriormente han sido clientes de algún banco, nos comparan con las aplicaciones de esos bancos, parece que hay cosas que extrañan.

>La aplicación que estamos probando es para iOS, sin embargo, para hacer un lanzamiento nacional necesitamos crear un app para Android.

>Nos falta acercarnos un poco más a los usuarios jóvenes, 100% digitales, los que usan Netflix, Uber, Spotify, Instagram, entre otros.

## 3. Objetivos iniciales del proyecto

- Utilizar los recursos brindados por la empresa para identificar los problemas que tiene la aplicación al momento de interactuar con los usuarios.
- Investigar a profundida el mercado peruano con respecto a las decisiones financieras de los más jóvenes del pais y su fuerza económica. 
- Rediseñar el producto ya existente, priorizando y solucionando los problemas identificados en el proceso de investigación. 
- Ampliar el mercado de la aplicación para un público más joven proponiendo mejoras y herramientas totalmente innovadoras.

## 4. Problemas identificados tanto a nivel de negocio como a nivel de usuario

1. Entrevistas a profundidad

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Affinity%20Map.png?raw=true)

- **Ahorro:** Ahorran al menos el 20% de sus sueldos para algún determinado fin. Es importante este método ya que los ayuda a planificar a futuro.
- **Seguridad:** Es importante que le brinde diferentes métodos de seguridad para el ingreso de la app (Huella, Contraseña, Face ID).
- **Token Digital:** El token les brinda seguridad para realizar sus transacciones pero les gustaría que se implemente otro método que no sea SMS.
- **Control:** Normalmente ingresan a su app bancaria para visualizar su saldo disponible y así llevar un control de sus egresos.

Muestra: 5 usuarios de entre 25 a 35 años 

2. Investigación de Mercado

- Según Reuters, el 81% de los jóvenes latinoamericanos ha usado, al menos una vez. una aplicación bancaria. Destacando los peruanos por su mayor frecuencia en estas apps.

- La investigacion (2019) se realizo a jovenes de entre 18 a 35 años, y el 64% de los peruanos prefiere hacer sus operaciones finacieras desde sus smartphones.

**Motivos:**
- Seguridad (82%)
- Verificacion de Saldo (72%)
- Practicidad
- Administracion

**Otros:**
- El 77% prefiere dinero en efectivo, mientras que el 32% utiliza tarjeta.
- La expectativa: facilitacion de transacciones sin necesidad de uso de tarjeta.

**Fuente:**

https://rpp.pe/economia/economia/jovenes-peruanos-usan-mas-apps-bancarias-que-el-resto-de-latinoamerica-noticia-1199802?ref=rpp
https://laprensa.peru.com/actualidad/noticia-como-se-comportan-jovenes-peruanos-ante-uso-aplicaciones-bancarias-88749


3. Testeos con Usuarios 

Decidimos realizar pruebas con usuarios del prototipo recibido para poder reconocer los principales puntos de dolor según prioridad.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Primer%20Testeo.png?raw=true)

Muestra: 5 pruebas con usuarios y 30 pruebas digitales.

- 18 a 25 : 9 personas (muestra más significativa)
- 26 a 35 : 16 personas
- 38 a 45 : 1 persona
- 45 a mas : 4 personas

Observación

En la misión #2, los usuarios tenían que iniciar sesión y programar un ahorro nuevo.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Mision%202.png?raw=true)

* 23 Usuarios se perdieron en la primera pantalla, sin saber donde hacer click.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Mapa%20de%20Calor%20Mision%202.jpg?raw=true)


4. User Persona 

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/User%20Persona.png?raw=true)


5. Customer Journey Map

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/CJM.png?raw=true)

## 4. Recomendaciones de próximos pasos para el banco con respecto al app

**1. Inicio de Sesión:** Se cambio la opción de inicio de sesión, donde el usuario tiene dos opciones: Poder ingresar con su DNI y una contraseña alfanumérica o con Face ID. Esto brinda accesibilidad rápida pues anteriormente se ingresaba con el número de cuenta y seguridad pues al contar con Face ID brinda confianza al usuario.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Inicio%20de%20Sesion.png?raw=true)

**2. Primera Vista:** Se eliminó la tarjeta pues no cumplia ninguna función, permaneció el saldo y se añadió la visualización de los ahorros programados con el avance de cada uno de ellos.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Primera%20Pantalla.png?raw=true)

**3. Mis Gastos:** El usuario podrá crear categorías de gastos para controlar sus egresos, puede incluir el monto máximo de esa categoría para que la aplicación le indique cuando sobrepase lo estimado. En caso eso suceda, aparecerá una cara triste y al hacer click, el detalle del exceso.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Mis%20Gastos.png?raw=true)
![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Mis%20Gastos%202.png?raw=true)

**4. Ahorros:** El usuario podrá crear categorías de ahorros para diferentes motivos que necesite. Podrá medir el avance y se debitará de manera manual o automática, según como el prefiera. En caso tenga más cuentas de ahorros, podrá elegir de donde desea que se debite.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Ahorros.png?raw=true)

**4. Operaciones:** Se agregó opciones de favoritos para cuentas de transferencias y pagos de servicios para hacer más sencillo el llenado de datos, además se agregó el token digital automático (sin SMS) para seguridad y comodidad del usuario. El token digital funciona por dispositivo y se activa en la agencia apenas apertura su cuenta de ahorros.

![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Pago%20de%20Servicios.png?raw=true)
![](https://github.com/andeluci/lim011-ux-financial-app/blob/master/IMG/Transferencias.png?raw=true)

## 6. KPI'S, Observaciones y NextSteps

* KPI

Para medir el avance exitoso del MVP: El usuario debe haber programado al menos 1 ahorro y haber realizado 3 operaciones (pagos - transferencias) al mes de tener la aplicación.

* Resultados de Testeos de Usuarios (2º Prototipo)

**- Ahorros:** Los usuarios no entendieron cómo programar un ahorro ya que es una funcionalidad totalmente nueva para ellos. Se tuvo que poner mensajes de apoyo.

**- Mis Gastos:** Los usuarios creyeron que esta función debitaba parte de su saldo disponible y no sabían que podían categorizar sus gatos. Se tuvo que poner mensajes de apoyo.

Muestra: 5 usuarios de entre 25 a 30 años.

* Next Steps

- Opción de cancelar ahorro
- Agregar gráficas en "Mis Gastos" para mayor control.
- Investigación sobre posible implementación de Código QR para transferencias.

## 7. Links

- Prototipo navegable [Marvel](https://marvelapp.com/84a6i0j/screen/65863170).

- Carpeta compartida [Drive](https://drive.google.com/drive/folders/1FPnBcaHZ6Un65szc2EQ4mKYjoXE-pkZ2?usp=sharing).

- Pruebas con Usuarios Estadísticas [Maze](https://maze.design/r/rd3n8tzk5itk0xe#mission-2-screen-3).

- 2da Prueba con Usuarios [Maze2](https://maze.design/r/hbdcok615j1cr).

- Presentacion Final [Canva](https://www.canva.com/design/DADyaPRXbUQ/VuqLhtGyjspE8jI0JO5c5g/view?utm_content=DADyaPRXbUQ&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton).

- Video en [Loom]( ).
