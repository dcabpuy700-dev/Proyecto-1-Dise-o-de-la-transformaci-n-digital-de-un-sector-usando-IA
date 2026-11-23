# Transformacion Digital de Extremo a Extremo con Inteligencia Artificial

**Proyecto 1: Diseño de la transformacion digital de un sector usando IA (Inteligencia Artificial)**

| Campo | Datos |
| :--- | :--- |
| **Nombre completo** | Dante Cabrera Puyana |
| **Fecha** | 23/11/2026 |
| **Asignatura** | Digitalizacion |

[ Ficha de la empresa ](#1-ficha-de-la-empresa) ─── [ Tecnologias ](#3-listado-de-tecnologias) ─── [ Diagrama ](#4-diagrama-it--ot) ─── [ Propuesta ](#5-propuesta-de-transformacion-digital) ─── [ Reflexion ](#6-reflexion-final)

---

## Fundamentos Teoricos

La digitalizacion consiste en usar tecnologia para que una empresa trabaje mejor, y es la base de su transformacion actual. Puede abordarse desde dos perspectivas que se complementan:

* **Digitalizacion en planta (OT, Tecnologia Operativa)**: se centra en la produccion, es decir, maquinas, sensores, lineas de envasado y control de calidad.
* **Digitalizacion en negocio (IT, Tecnologias de la Informacion)**: se centra en la gestion y la administracion, como compras, ventas, almacen y finanzas.

Al digitalizar de extremo a extremo, la empresa conecta ambas areas. Asi trabaja con mas eficiencia, compite mejor y toma decisiones basadas en datos. La IA es la pieza que permite mejorar procesos, anticipar lo que va a pasar y aportar mas valor en las dos areas.

---

## 1. Ficha de la Empresa

Empresa ficticia del sector de la **industria alimentaria (conservas de pescado)**.

| Caracteristica | Detalle |
| :--- | :--- |
| **Nombre** | Conservas del Cantabrico S.A. (Sociedad Anonima) |
| **Sector** | Industria alimentaria, conservas de pescado y marisco. |
| **Tamaño** | Mediana empresa: 180 empleados y 28 millones de euros de facturacion anual. |
| **Ubicacion** | Fabrica en Cantabria, con almacen propio. |
| **Productos** | Atun, bonito, anchoas y sardinillas en lata y en frasco de vidrio. |
| **Clientes** | Grandes cadenas de supermercados (65 %), hosteleria y restauracion (HORECA, Hoteles, Restaurantes y Cafeterias) (20 %) y venta online y exportacion (15 %). |
| **Situacion actual** | Lineas de envasado con maquinas de distintas epocas, control de calidad manual por muestreo (se revisan solo algunas unidades), un programa de gestion basico (ERP, Planificacion de Recursos Empresariales) y prevision de ventas en hojas de calculo. |

**Problemas principales**

* Paradas imprevistas por averias en los esterilizadores a presion (autoclaves) y en las maquinas que cierran las latas (selladoras).
* Perdidas de producto y retiradas del mercado por defectos de cierre o de etiquetado que se detectan tarde.
* Falta de producto o exceso de existencias (stock) porque la prevision de ventas es poco precisa.
* Dificultad para seguir el recorrido completo de cada lote, desde el pescado recibido hasta el pedido del cliente (lo que se llama trazabilidad).

---

## 2. Digitalizacion en Planta frente a Negocio

| Aspecto | Digitalizacion en Planta (OT) | Digitalizacion en Negocio (IT) |
| :--- | :--- | :--- |
| **Foco** | Produccion y maquinas. | Gestion, administracion y relacion con el cliente. |
| **Datos** | Temperaturas, presiones, vibraciones e imagenes de la linea. | Pedidos, inventario, facturas e historial de ventas. |
| **Sistemas tipicos** | Automatas que controlan las maquinas (PLC, Controladores Logicos Programables), pantallas de supervision de la fabrica (SCADA, Supervision, Control y Adquisicion de Datos), sistema que registra que se fabrica y cuando (MES, Sistema de Ejecucion de Fabricacion) y sensores conectados a internet (IIoT, Internet Industrial de las Cosas). | Programa de gestion (ERP), programa de gestion de clientes (CRM, Gestion de la Relacion con el Cliente), paneles de indicadores (BI, Inteligencia de Negocio) y tienda online. |
| **Prioridad** | Que las maquinas funcionen siempre y con seguridad, en tiempo real. | Que los datos sean correctos, se analicen bien y esten protegidos. |
| **Aporte de la IA** | Anticipar averias, detectar defectos y ajustar las maquinas. | Anticipar las ventas, atender consultas de forma automatica y ayudar a decidir. |

---

## 3. Listado de Tecnologias

Se proponen cinco tecnologias: tres para planta y dos para negocio.

| N.º | Tecnologia | Ambito | Que mejora |
| :--- | :--- | :--- | :--- |
| 1 | **Sensores conectados (IIoT) y sistema de registro de la produccion (MES)** | Planta | Recogida de datos de las lineas en tiempo real y seguimiento de cada lote. |
| 2 | **Mantenimiento predictivo con IA** (avisa de una averia antes de que ocurra) | Planta | Cuidado de esterilizadores, selladoras y cintas transportadoras. |
| 3 | **Vision artificial** (camaras con IA que reconocen defectos) | Planta | Revision de cierres, etiquetas y llenado de cada lata. |
| 4 | **Programa de gestion (ERP) con prevision de ventas mediante IA** | Negocio | Planificacion de compras, produccion y existencias. |
| 5 | **Programa de clientes (CRM) con asistente virtual** (chatbot, un robot que conversa por escrito) | Negocio | Atencion al cliente, gestion de pedidos y deteccion de oportunidades. |

### Justificacion de la seleccion

1. **Sensores conectados y MES**: son la base de todo el proyecto. Sin datos fiables de la linea no se puede usar IA. Ademas permiten seguir el recorrido de cada lote desde la materia prima hasta el cliente.
2. **Mantenimiento predictivo**: los sensores miden vibracion y temperatura, y un modelo de IA detecta señales de averia. Asi se reducen las paradas imprevistas y las maquinas duran mas.
3. **Vision artificial**: sustituye la revision de unas pocas latas por la revision de todas ellas. Detecta defectos al momento y reduce perdidas y riesgos de retirada de producto.
4. **ERP con prevision de ventas**: un modelo de IA estudia el historial de ventas, las epocas del año y las promociones para calcular cuanto comprar y fabricar. Asi hay menos faltas de producto y menos sobrante.
5. **CRM con asistente virtual**: responde automaticamente a las preguntas habituales, como el estado de un pedido o el catalogo, y deja al equipo comercial mas tiempo para casos importantes. Tambien avisa de clientes que podrian dejar de comprar.

---

## 4. Diagrama IT / OT

El diagrama muestra como se organizan la planta (OT) y la gestion (IT) de la empresa, y como la IA influye en los procesos clave.

![diagrama](../src/diagrama_digi.png)

**Como leer el diagrama**

* La parte de **OT** (planta) genera los datos de las maquinas y las imagenes de la linea.
* La parte de **IA** los convierte en avisos, predicciones y recomendaciones.
* La parte de **IT** (gestion) usa esa informacion para planificar, comprar, vender y decidir, y devuelve a la planta el plan de produccion. Asi se cierra el ciclo de extremo a extremo.

---

## 5. Propuesta de Transformacion Digital

### Fase 1: Conectar y recoger datos

Se instalan sensores en los esterilizadores, las selladoras y las cintas, y se pone en marcha el MES, que anota cada lote que se fabrica. Se conecta con el ERP para que planta y gestion compartan la misma informacion.

### Fase 2: Usar IA en la planta

* Se entrenan modelos de mantenimiento predictivo con el historial de averias y las lecturas de los sensores.
* Se instalan camaras con vision artificial al final del sellado y en el etiquetado, con retirada automatica de las latas defectuosas.

### Fase 3: Usar IA en el negocio

* El modelo de prevision de ventas sustituye a las hojas de calculo y orienta el plan de produccion y de compras.
* El asistente virtual atiende consultas de clientes y el CRM señala las cuentas mas importantes y los clientes que podrian marcharse.

### Fase 4: Unir todo y mejorar de forma continua

El panel de indicadores (BI) reune datos de planta y de gestion. Los modelos se actualizan cada cierto tiempo con informacion nueva para que sigan acertando.

### Cambios en los procesos y en las personas

| Proceso | Antes | Despues |
| :--- | :--- | :--- |
| **Mantenimiento** | Se repara cuando se averia o en fechas fijas. | Se interviene segun el estado real de la maquina. |
| **Control de calidad** | Se revisan algunas unidades a mano. | Se revisan todas las unidades durante la produccion. |
| **Planificacion** | Hojas de calculo e intuicion. | Prevision automatica y plan conectado con el ERP. |
| **Trazabilidad** | Parcial, con registros en papel. | Completa, del lote de materia prima al pedido. |
| **Atencion al cliente** | Telefono y correo, en horario limitado. | Asistente virtual las 24 horas y equipo comercial dedicado a casos complejos. |

Los operarios pasan de tareas repetitivas a vigilar los sistemas y analizar datos, por lo que se incluye un plan de formacion en competencias digitales. Los equipos de IT y de OT trabajan juntos y con las mismas normas de proteccion frente a ciberataques.

### Ventajas operativas

* Menos paradas imprevistas y lineas disponibles mas tiempo.
* Menos perdidas de producto y menos retiradas del mercado.
* Menos producto parado en el almacen y menos faltas de existencias.
* Seguimiento completo de cada lote ante inspecciones y alertas alimentarias.

### Ventajas competitivas

* Mas fiabilidad de servicio frente a las grandes cadenas, que penalizan los retrasos e incumplimientos.
* Calidad mas constante, lo que refuerza la marca y facilita vender en el extranjero.
* Capacidad de reaccion rapida ante cambios en la demanda y en el precio del pescado.
* Los datos propios se convierten en un valor estrategico a largo plazo, con opciones de futuro como un codigo en la lata con el que el consumidor consulte el origen del producto.

---

## 6. Reflexion Final

### Importancia presente de la IA

La IA ya no es una promesa de futuro. Hoy permite a empresas como Conservas del Cantabrico evitar paradas con el mantenimiento predictivo, revisar cada lata con vision artificial y ajustar la produccion a la demanda real. Son aplicaciones probadas, con resultados medibles y con herramientas al alcance tambien de una mediana empresa.

### Sectores con mayor uso de IA y comparacion

| Sector | Aplicacion destacada de la IA | Comparacion con la industria alimentaria |
| :--- | :--- | :--- |
| **Automocion** | Camaras que revisan el montaje, robots que trabajan junto a las personas y mantenimiento predictivo. | Esta mas avanzada y automatizada. La alimentaria usa las mismas tecnicas, pero con menos volumen y mas variedad de productos. |
| **Banca y seguros** | Deteccion de fraudes, calculo del riesgo de cada cliente y atencion automatica. | Muy avanzada en datos y gestion. Sirve de modelo para el CRM y el analisis de clientes. |
| **Salud** | Diagnostico a partir de imagenes medicas y busqueda de nuevos medicamentos. | Comparte la vision artificial, pero con normas mucho mas estrictas. |
| **Comercio y transporte** | Prevision de ventas, rutas mas eficientes y recomendaciones personalizadas. | Es el mejor modelo para prever la demanda y gestionar las existencias. |
| **Energia** | Prediccion del consumo y mantenimiento de instalaciones. | Su mantenimiento predictivo se puede aplicar directamente en la fabrica. |

### Influencia de la IA en el sector alimentario

* **Hoy**: se usa para clasificar producto y controlar su calidad con camaras, seguir cada lote, prever ventas y reducir el consumo de energia en procesos como el calentado y esterilizado.
* **Futuro**: se preven replicas virtuales de la fabrica (gemelos digitales) para probar cambios en el ordenador antes de aplicarlos, compras ajustadas a las capturas de pescado y a los precios, medicion y reduccion del impacto ambiental y del desperdicio con ayuda de IA, y una produccion mas adaptada a pedidos personalizados.

> "La IA no sustituye a la planta ni al negocio: los conecta, y esa conexion es la ventaja competitiva."

---

## Resumen de la Entrega

| Apartado | Seccion de este documento |
| :--- | :--- |
| Ficha de la empresa | [1. Ficha de la Empresa](#1-ficha-de-la-empresa) |
| Listado de tecnologias | [3. Listado de Tecnologias](#3-listado-de-tecnologias) |
| Diagrama Mermaid | [4. Diagrama IT / OT](#4-diagrama-it--ot) |
| Propuesta de transformacion digital | [5. Propuesta de Transformacion Digital](#5-propuesta-de-transformacion-digital) |
| Reflexion final | [6. Reflexion Final](#6-reflexion-final) |

***
_Documento del Proyecto 1 sobre transformacion digital con IA. [Volver al inicio](#transformacion-digital-de-extremo-a-extremo-con-inteligencia-artificial)_
