# tp9f
INSTRUCCIONES DE USO. SIMULADOR DE LEDS CONECTADOS A PUERTOS

USO DEL TECLADO:

Para poder cambiar el estado de un led individualmente, el usuario debe asegurarse de tener desactivado el TAB
(comienza desactivado por defecto). 
Además el usuario debe tener en cuenta que puerto se encuentra modificando.
Por defecto, el puerto a modificar es el A. Si el usuario quiere cambiar de puerto, simplemente
debe presionar la tecla que represente al nombre del puerto.

Si se encuentra modificando el puerto D, el usuario debe ingresar dos numeros para que se interprete un led.
ejemplo: (estamos situados en el puerto D)
se presion la tecla 0 --- > el programa espera el ingreso de la segunda tecla
se presion la tecla 6 --- > se prende el led 6.
se presion la tecla 5 --- > el programa espera el ingreso de la segunda tecla
se presion la tecla 6 --- > no pasa nada, porque no existe el led 56

Para poder cambiar varios leds de manera simultánea, el usuario debe activar el TAB presionando la tecla TAB una vez.
Para desactivar el TAB debe volver a presionar la tecla.
Una vez activado el TAB, se puede llamar a la funcion blink (tecla b), clear (c) y set (s).
Estas funciones tambien tienen en cuenta en que puerto me encuentro modificando.


USO DEL MOUSE:

Con el mouse el usuario puede cambiar individualmente cada led. Debe tener en cuenta que cada vez que el usuario hace uso 
del mouse, cambia a modificar el puerto D.

Ejemplo:

Me encuentro inicialmente en puerto A. 
click en led 0 del puerto A.
presiono tecla 0 (uso del teclado) -----> se queda esperando segunda tecla

Nota: si el usuario presiona el fondo del display, este cambia su imagen.




