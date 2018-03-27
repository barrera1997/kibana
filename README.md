# Dashboard SBD Social
Para importar el Dashboard, lo primero que tenemos que hacer es conectarnos al UI de Kibana (<Nombre_Servidor>:5601). 

Una vez conectados, tendremos que definir el índice que vamos a usar para visualizar los datos. En nuestro caso, el índice es sbd* y el campo sobre el que haremos búsquedas temporales es media_tiemstamp.

![Alt text](./Paso1_Index_Pattern.png?raw=true "Paso1_Index_Pattern.")

Pulsamos en "Create" y aparecerá la siguiente pantalla:

![Alt text](./Paso2_Management.png?raw=true "Paso2_Management.")

Pulsamos en "Saved Objects" y nos llevará a la siguiente pantalla:

![Alt text](./Paso3_SaveObjects.png?raw=true "Paso3_SaveObjects.")

Pulsamos en "Import" y aparecerá la siguiente pantalla:

![Alt text](./Paso4_Import_JSON.png?raw=true "Paso4_Import_JSON.")

Elegimos el JSON donde se encuentra nuestro Dashboard y pulsamos en "Abrir". Aparecerá la siguiente pantalla:

![Alt text](./Paso5_OverwriteAll.png?raw=true "Paso5_OverwriteAll.")

Pulsamos sobre "Yes, overwrite all". Nos llevará a la siguiente pantalla:

![Alt text](./Paso6_DashboardImport.png?raw=true "Paso6_DashboardImport.")

Pulsamos sobre nuestro Dashboard (en este caso Dashboard_Prueba) y obtendremos la siguiente pantalla:

![Alt text](./Paso7_ViewDashboard.png?raw=true "Paso7_ViewDashboard.")

Pulsamos sobre "View Dashboard" y ya tenemos nuestro Dashboard importado.

![Alt text](./Dashboard_Prueba.png?raw=true "Dashboard_Prueba.")
