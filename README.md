# Challenge #2 OracleONE/AluraLatam

### Descripción:
Éste challenge consistió en crear un programa que permita al usuario escoger un tipo de conversión de monedas a través de un menú en la terminal, al escoger un tipo de conversión se procede a pedir una cantidad a convertir y se muestra el resultado de dicha conversión. Las conversiones se realizan con la ayuda de la API Exchange Rate.

## Funcionalidades

### Menú de opciones.
El programa muestra un menú de opciones al ejecutarse:<br>
![Primer menú](https://github.com/Ismael-Avalos/Conversor/assets/156988387/0bf09ed8-ff46-4175-9486-639ac6b00151)

### Validación y manejo de excepción de texto.
Una vez el usuario digita una opción el programa hace dos validaciones.
Validación del rango de números especificados:
![Validación](https://github.com/Ismael-Avalos/Conversor/assets/156988387/9771de7d-d10f-43df-a778-7daedbf4a045)<br>
Manejo de excepcion en caso de ingresar texto:
![Validación](https://github.com/Ismael-Avalos/Conversor/assets/156988387/fed31f02-e547-46c8-b023-4046dd392e00)<br>
Si la opción es válida se solicita el monto a convertir, se devuelve el resultado y vuelve al primer menú para seguir haciendo conversiones.
![Resultado](https://github.com/Ismael-Avalos/Conversor/assets/156988387/1641e26f-d7b6-445a-94fd-2301340e8a88)

### Consulta a la API:
![Consulta a la API](https://github.com/Ismael-Avalos/Conversor/assets/156988387/f50b459a-c88a-4ead-9548-eeed0811f33c)

### Clase modelo:
De tipo record.

![Clase modelo](https://github.com/Ismael-Avalos/Conversor/assets/156988387/0822fb14-ee3e-45cf-927d-216fab554afc)
