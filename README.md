# PRACTICAS PROFESIONALES

IFTS 18 

Integrantes 
  - Yamila Villarnovo | PRESENTACION DOCUMENTACION TESTING
  - Joaquin Sosa      | DASHBOARD BI DOCUMENTACION
  - Victor Mendez     | FRONTEND DOCUMENTACIOON
  - Agustina Perez    | FRONTEND DOCUMENTACION
  - Anderson Ocaña    | BACKEND DOCUMENTACION

## GANTT

Calculo aproximado de tiempos para el desarrollo del TP

![](/images/gantt.png)

## Summary:

  El proyecto se entabla de crear un software integrado con distintas tecnologias tanto BI, Bases de datos y variantes, dependiendo de la necesidad del usuario, creación de un Front End.

## Tecnica:
  Usamos la fuente de datos del usuario, google sheets, de la cual por medio de su propuesta obtuvimos el siguiente DTO:
  ```
  let type_dto = {
    uuid : string,
    fecha_carga : date,
    area: string,
    personal:number,
    link: string,
    email: string,
    valor_facturacion:float
  }
  
  ```
 
 ### BackEnd:
 La herramienta para hacer la API, en un inicio se pensó usar Flask, sin embargo se migró a una herramienta llamada [SheetDB.io](https://sheetdb.io/) dado a su practicidad y a lo que estabamos apuntando como MVP para un termino de negocio inicial.
 
 ### FrontEnd:
 
 Se realiza el desarrallo usando una landing page, en la cual podemos requerir  el ingreso de la información, asi como también el filtrado de la información que queremos visualizar, de manera puntual
 
 ### Herramienta Bi
 Se decide usar Looker (DATA STUDIO), pues la fuente cuenta con una cantidad de registros menores a 3k , por lo tanto es una herramienta perfecta de manera viz, pues el máximo permitido es de 1M; ergo al poder utilizar esta herramienta para una presentación de MVP, es ideal.
 
 Se colocan como datos de filtrado por año, área y estimaciones que nos despliegan de los valores de facturación final obteniendo un ranking coherente de las áreas respectivas.
 

## CONCLUSIONES SOBRE EL SOFTWARE

El software hace una ingesta en el tablero, la cual  nos permite visualizar la cantidad de registros, evaluando las áreas en las cuales tienen mayor cantidad de registros almacenados, y en que momentos se empiezan a tener mayor cantidad de inserciones y concurrencia.
Esto nos permite evaluar  la cantidad de servidores o nodos que podemos generar para que la inserción sea más eficiente y no presente dificultades para el usuario final, permitiendo una fidelización del usuario final a este producto.

 
# DATA USADA & LINKS




## DIAGRAMA ONTOLOGICO 
El diagrama inicial es: 
  [DIAGRAMA ONTOLOGICO USADO PARA EL PROYECTO](https://drive.google.com/file/d/1MaRsFZ5jyiCtx7RcAKJqUtWdBasP_rfh/view?usp=share_link)
  
  [DIAGRAMA EN EXCALIDRAW](https://excalidraw.com/#json=MGnp3qWq24SjSlOfAMkEa,rlMOpbzqcHtCjhgBx2RRUQ)

## BASE DE DATOS
  [BASE DE DATOS >> GOOGLE SHEETS](https://docs.google.com/spreadsheets/d/1UmLKL1Iobm_LmqZrgC1Pa7FEd9XipdVNIs0Luyryg4w/edit#gid=0)

## VISUALIZACION UTILIZANDO LOOKER|DATASTUDIO
  [DATA STUDIO >> TABLERO DE TOMA DE DECISIONES](https://datastudio.google.com/reporting/e7c0230a-695f-4d1f-8739-5aca25e415fd)

## API GENERADA POR DB SHEETS
  [API GENERADORA DE CONEXION](https://sheetdb.io/api/v1/l424ztv3cd1h4)
  
## FRONT END DE CARGA
  [REPOSITORIO DEL FRONT](https://github.com/vmendezrojas95/agendaGastos.git)
  
## PRESENTACIÓN DEL TRABAJO
  [ PRESENTACION REALIZADA PARA EL TP]

## TRELLO
  [TRELLO PRACTICAS LABORALES](https://trello.com/b/t1Clc0Ch/tp3-gestor-de-toma-de-bi)

