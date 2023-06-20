# BOT Descarga de Comprobantes emitidos en AFIP y envío por mail

Bot de para la descarga de Comprobantes Emitidos en AFIP del servicio de Comprobantes en Línea y envío por mail de manera masiva de un solo contribuyente.

---

El licenciamiento es con GPL (es decir que no se puede distribuir comercialmente, solamente GRATIS). y si se utiliza este el código, su derivado también debe ser distribuido abierta y gratuitamente.

---

## Ejecución del BOT

Los pasos para ejecutar el bot son los siguientes:

1. Crearse una cuenta en UiPath ([https://www.uipath.com/](https://www.uipath.com/)).

2. Descargar el Uipath Studio (https://www.uipath.com/studio) en la versión Community (es gratuita).

3. Instalar la version el Studio (no la Studio X).

4. Descargar el BOT. Acá hay 3 opciones:
   
   1. Descargar el ZIP.
   
   2. Descargarlo con la integración de GIT desde el Uipath.
   
   3. Descargar el repositorio con GIT utilizando el comando 
   
        ```bash	
        git clone https://github.com/abustosp/Descargar-y-Enviar-Facturas-de-1-contribuyente.git
        ```

5. Una vez Descargados los archivos se debe:
   
   1. Abrir el project.json o archivo .xaml
   
   2. Ejecutarlo (hacer click en el boton de "Play").

---

## Particularidades del BOT:

- El Bot corre en Firefox (se puede configurar para Chrome pero se recomienda el primero por temas de rendimiento) y en Windows 10 cómo mínimo

- Los datos de la facturas son los provenientes al archivi de Mis Comprobantes Emitidos

- Para Ejecutar el BOT se debe completar la información en el Excel (hay que tener en cuenta el formato regional de Excel, en algunos casos hay que reemplazar en todas las fórmulas los AAAA por YYYY).

- En caso que no se guarden los Archivos con el nombre definido en el Excel se debe ejecutar el bot que contiene en su nombre "sin ST" (sin no existe se subirá proximamente)

- Las ubicaciones del Excel deben ir desde el Disco hasta la Ubicación completa con un backslash final (ejemplo: 'C:\Users\Agustin Bustos\Desktop\TEST\')
  
  - Los de la ventana emergente inicial van sin el último backslash (ejemplo: 'C:\Users\Agustin Bustos\Desktop\Test') y es importante que esa ubicación exista. Esta ubicación se utiliza solamente cuando la direccion de descarga del Excel esta vacío

---

## Aclaraciones

- La utilización del bot es bajo tu propia responsabilidad.

- Si se comparte debe ser de manera GRATUITA, ya que la licencia es bajo GPL 3. También los bots derivados deben seguir la misma licencia gratuita.

---

## Videos que pueden ser de utilidad

1. Descarga de BOTs de repositorios de GitHub con Uipath: https://youtu.be/hD5BH7YzABw

2. Descarga e instalación de GIT para descargar repositorios (en caso que no esta habilitada la funcionalidad nativa de Clonar los repositorios): https://youtu.be/ujk27tRdA80

---

Cualquier cosa pueden contactarme en:

- https://www.linkedin.com/in/agust%C3%ADn-bustos-piasentini-468446122/

- https://www.youtube.com/user/agustinbustosp

- whatsapp al https://wa.me/+5493764224695

---

<br/>

## 💰 Acepto donaciones para mantener el proyecto libre y gratuito

<br/>

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/agustinbustosp) <!-- [<img src="http://ketekipo.com.ar/wp-content/uploads/2020/05/mercado-pago.png" alt="Image" height="30" width="100\">](https://paypal.me/paypal.me/agustinbustosp) -->

<!-- [![Cafecito](https://img.shields.io/badge/-Cafecito-9cf?style=for-the-badge)](https://cafecito.app/abustos) -->

<!-- [<img src="https://santanderpost.com.ar/wp-content/uploads/2022/02/Cafecito-.jpg" title="Cafecito" height="30" width="65\">](https://cafecito.app/abustos) -->

[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_5.svg)](https://cafecito.app/abustos)


<br/>

## 💰 Y También en Pesos Argentinos

<br/>

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20100-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2JBdGez)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20500-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2CwfjKE)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%201.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/21Xvpig)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%205.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1s4D4mM)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%2010.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1n9cimr)
