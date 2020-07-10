# Proyecto_Integrador
## Servicio Web para una Agencia de Viajes 
## Integrantes del Equipo 
### Elsa Cruz Ramirez
### Geraldine Ortiz Fernández 

### Servicios 
1. Crucero [URL del servicio](http://3.82.213.195:9191/cruceroelsa.wsdl)
2. Aereolínea [URL del servicio](http://54.90.84.87:8080/aeropuerto.wsdl)
3. Banco [URL del servicio](http://3.87.203.171:8080/banco.wsdl)

### Requerimientos 
>Crucero 
- Reservación 
- Actualizar reservación 
- Eliminar reservación 

>Aereolínea 
- Agregar pasajero 
- Actualizar pasajero 
- Eliminar pasajero 

>Banco 
- Realizar pago 
- Realizar reembolso 

### Especificación de funciones 
>Crucero 
#### Reservación 
| Atributo | Tipo | Método |
| -------- | ---- | ------ |
| noReservacion | String | setNoReservacion() / getNoeservacion() |
| nombreUsuario | String | setNombreUsuario() / getNombreUsuario() |
| fechaSalida | String | setFechaSalida() / getFechaSalida() |
| horaSalida | String | setHoraSalida() / getHoraSalida() |
| costo | int | setCosto() / getCosto() |
