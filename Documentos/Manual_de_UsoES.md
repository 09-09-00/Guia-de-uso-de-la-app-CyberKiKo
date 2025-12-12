# GUIA DE USO DE LA APLICACION CYBERKIKO 

Este manual detalla los pasos para usar la app de Cyberkiko y todas sus funciones de manera sencilla y practica. 

## **1. Incio de Sesion** 
![Imagen de Inicio de Sesion](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/Inicio.jpeg)

### :warning:  **Importante:** 
Esta parte ya está configurada en los dispositivos Zebra.
No es necesario modificar la URL ni el puerto a menos que la aplicación se cierre
inesperadamente o se pierda la conexión.

* Si esto sucede, en la vista Ajustes (si no consigue entrar, pueda reinstalar la aplicación, el
enlace
se encuentra en el correo de la aplicación Gmail, y es el archivo de nombre
 CyberKiko (2).apk), verifique o coloque los siguientes datos:
 URL Base: https://idempiere-mo.monalisa.com.py
 Puerto Base: 8443
* Luego presione Confirmar (siempre hacer Enter).
* Para ingresar (no hace falta tocar nada si ya le aparece)
* **1. Usuario:** moapp
* **2. Contraseña:** Monalisapy
Presione **Iniciar.**

## **2. Selección de Rol**
![Imagen de Inicio de Sesion](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/rol.jpg)

Después del inicio de sesión, aparecerá una pantalla para seleccionar:

 * **Grupo Empresarial**
 * **Rol**
 * **Organización**
 * **Depósito**

Seleccione las opciones correspondientes y presione **Confirmar.**

## **3. Menu de Opciones**

![Imagen Seleccion de Rol](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/vista_menu.jpg)

Al ingresar, verá tres opciones principales:
* **Barcode (Código de Barras)**
* **Receipt (Recibo)**
* **Shipment (Envío)**
  
La función que utilizaremos es **Shipment**

## **4.1 Vista del Shipment**
![Imagen del Shipment](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/shipment_filtro_cat.jpg)

Esta es la pantalla principal para imprimir etiquetas.
### **Ingreso del Shipment**

Hay **dos formas** de ingresar el número del Shipment:
1. **Digitando** el número manualmente.
2. **Escaneando** el código con el lector.
Para activar el escáner, presione el **ícono del lector** (el dibujo del escáner) al lado del
campo.
Esto permitirá que la aplicación reconozca el código de barras.

![Imagen de etiqueta del Shipment](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/shipment_etiquetas.jpg)

* Si desea imprimir todas las etiquetas, debe seleccionar **todas las etiqueta**s antes
de presionar el botón de **imprimir.**
* Si solo desea imprimir una etiqueta específica, seleccione **únicamente esa
etiqueta** en la lista.

## **4.2 Vista del Receipt**
![Imagen del Receipt](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/receipt_doc.jpg)

En esta pantalla encontraremos la vista para imprimir los recibos.

### **Ingreso del Recibo**

En el Recibo encontraremos:
* **Número del recibo**
* **Catálogo**
* **Selección de Impresora**
* **Etiquetas**
  
Hay **dos formas** de ingresar el número del Recibo
1. **Digitando** el número manualmente.
2. **Escaneando** el código con el lector.
Para activar el escáner, presione el **ícono del lector** (el dibujo del escáner) al lado del
campo.
Esto permitirá que la aplicación reconozca el código de barras.

![Imagen de etiqueta](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/receipt_etiquetas.jpg)

* Si desea imprimir todas las etiquetas, debe seleccionar **todas las etiquetas** antes
   de presionar el botón de imprimir.
* Si solo desea imprimir una etiqueta específica, seleccione **únicamente esa
   etiqueta** en la lista.

## **4.3 Vista del Barcode**
![Imagen del Barcode](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/vista_upc.jpg)

En esta pantalla se encuentra la vista para imprimir etiquetas mediante código de barras.

### **Ingreso del Barcode**
Para ingresar el número del código de barras se escanea el **código UPC**, el sistema obtiene
automáticamente los datos del producto, luego se repiten los pasos de la impresora y se
selecciona la etiqueta.

📍Para activar el escáner, presione el **ícono del lector** (el dibujo del escáner) al lado del
campo.
  * En el campo **Cant.**, se debe indicar la cantidad de **etiquetas que se desea
    imprimir.**
  * En la opción **Pricelist**, se debe seleccionar **“Elegir lista de precios”.**
    Una vez completados todos los datos, se presiona el botón **Imprimir** para finalizar el
    proceso.

## **5. Visualización de datos**

La aplicación traerá los datos del Shipment y los mostrará en una tabla.
### **Allí podrá ver:**
* El **UPC** de los productos.
* La **cantidad** disponible de cada uno.
  
Los resultados se muestran en **orden descendente** según el campo Line.

## **6. Selección de impresora**

![Imagen de Seleccion](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/Impresoraip.jpg)

Luego, debe escanear la impresora que desea utilizar.

* Presione el **ícono del escáner** junto al campo Impresora.
* Escanee el código de la impresora.

## **7. Impresión de etiquetas**

Seleccione el tipo de **Etiqueta** que desea utilizar en la lista desplegable.
En el campo **Línea**, por defecto aparece el valor **0.**

![Imagen de etiqueta](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/etiquetas.jpg)

Si deja el **0** y presiona **Enter**, la aplicación imprimirá todas las líneas del Envío.
Si desea imprimir solo una línea específica, escriba el número de línea y presione **Enter.**

![Imagen de la Impresora](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/impresora_etiqueta.jpg)

Finalmente, presione el botón **Imprimir** para generar las etiquetas.

# **Ejemplo de cómo debe salir:** ⬇️

## **1. Documento a escanear** 

![Imagen del ejemplo de documento](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/ejmplo_documento.jpg)

## **2.  Indicaciones para la impresión** ️ℹ️

Etiquetas en formato 40x28, se imprime primero una etiqueta GUÍA, para identificar 
Producto, Número de Línea (se imprime en orden) y Cantidad, luego se imprimen 
las X etiquetas, nótese que para las categorías de Testers, Muestras y Gpws &
Promociones solo se imprime la etiqueta guía.

![Imagen del ejemplo de documento](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/Impresion.jpg
)

