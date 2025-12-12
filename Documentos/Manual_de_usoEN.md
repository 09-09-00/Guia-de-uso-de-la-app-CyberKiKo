# CYBERKIKO APPLICATION USER GUIDE :star:

This manual details the steps to use the Cyberkiko app and all its functions in a simple and practical way.
## **Login**

![Login Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/Inicio.jpeg)

### :warning:   **Important**
This part is already configured on Zebra devices.
You don't need to modify the URL or port unless the application closes unexpectedly or the connection is lost.

* If this happens, in the Settings view (if you can't access it, you can reinstall the application; the link is in the Gmail email and is a file
named CyberKiko (2).apk), verify or enter the following information:
Base URL: https://idempiere-mo.monalisa.com.py

Base Port: 8443
* Then press Confirm (always press Enter).

* To log in (you don't need to change anything if it already appears)
* **1. Username:** moapp
* **2. Password:** Monalisapy
* Press **Start.**
## **2. Role Selection**
![Login Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/rol.jpg)

After logging in, a screen will appear where you can select:

* **Business Group**

* **Role**

* **Organization**

* **Warehouse**
Select the corresponding options and press **Confirm.**

## **3. Options Menu**

![Role Selection Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/vista_menu.jpg)

Upon entering, you will see three main options:
* **Barcode**
* **Receipt**
* **Shipment**

The function we will use is **Shipment**

## **4.1 Shipment View**
![Shipment Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/shipment_filtro_cat.jpg)

This is the main screen for printing labels.

### **Entering the Shipment Number**

There are **two ways** to enter the Shipment Number:

1. **By typing** the number manually.
2. **By scanning** the code with the reader.
To activate the scanner, press the **reader icon** (the scanner icon) next to the field.
This will allow the application to recognize the barcode.

![Shipment Label Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/shipment_etiquetas.jpg)

* To print all labels, select **all labels** before pressing the **print** button.
* To print only a specific label, select **only that label** from the list.

## **4.2 Receipt View**
![Receipt Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/receipt_doc.jpg)

This screen displays the view for printing receipts.

### **Receipt Entry**

The receipt includes:
* **Receipt Number**
* **Catalog**
* **Printer Selection**
* **Labels**

There are **two ways** to enter the receipt number:
1. **By manually typing** the number.
2. **By scanning** the code with the reader.
To activate the scanner, press the **reader icon** (the scanner icon) next to the field.
This will allow the application to recognize the barcode.

![Label Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/receipt_etiquetas.jpg)

* If you want to print all labels, you must select **all labels** before pressing the print button.
* If you only want to print a specific label, select **only that label** from the list.

## **4.3 Barcode View**
![Barcode Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/vista_upc.jpg)

This screen displays the view for printing labels using barcodes.

### **Barcode Entry**
To enter the barcode number, scan the **UPC code**. The system automatically retrieves the product data. Then, repeat the printer steps and select the label.

To activate the scanner, press the **scanner icon** (the scanner image) next to the field.
* In the **Qty.** field, enter the number of **labels you wish to print.**
* In the **Pricelist** option, select **“Choose price list”.**
Once all the data is completed, press the **Print** button to finish the process.

## **5. Data Display**

The application will retrieve the Shipment data and display it in a table.

### **There you will see:**
* The **UPC** of the products.
* The **quantity** available for each product.
The results are displayed in **descending order** according to the Line field.

## **6. Printer Selection**

![Selection Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/Impresoraip.jpg)

Next, you must scan the printer you want to use.

* Press the **scanner icon** next to the Printer field.

* Scan the printer code.

## **7. Label Printing**

Select the type of **Label** you want to use from the dropdown list.
The default value in the **Line** field is **0**.

![Label Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/etiquetas.jpg)

If you leave it at **0** and press **Enter**, the application will print all the lines in the shipment.
If you want to print only a specific line, type the line number and press **Enter**.

![Printer Image](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/impresora_etiqueta.jpg)

Finally, press the **Print** button to generate the labels.
# **Example of how it should look:** ⬇️

## **1. Document to scan** 

![Image of the example document](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/ejmplo_documento.jpg)

## **2. Printing instructions** ℹ️
Labels in 40x28 format. First, print a GUIDE label to identify the
Product, Line Number (printed in order), and Quantity. Then print the X labels. Note that for the Testers, Samples, and Gpws & Promotions categories, only the guide label is printed.
![Image of the sample document](https://github.com/09-09-00/Guia-de-uso-de-la-app-CyberKiKo/blob/main/Documentos/Imagenes/Impresion.jpg
)
