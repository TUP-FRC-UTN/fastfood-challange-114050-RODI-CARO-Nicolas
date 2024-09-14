[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/1L-OSgS7)
# Challenge - FastFood

## Descripción

La idea es hacer una App que nos permita gestionar un restaurant de comida rápida:
- Ingresar un nuevo pedido
- Mostrarlo como "pendiente"
- Poder tomarlo en cocina para cocinar
- Una vez terminado notificar que se encuentra listo para entregar
- Entregarlo

La aplicación constará de 4 Componentes
- POS: Point of Sell (Donde se hacen los pedidos)
- Kitchen: Lugar donde se toman y cocinan los pedidos
- Delivery Point: Donde entegamos el pedido
- Restaurant: La aplicación que engloba los componentes

En este ejercicio podrán hacer uso de Input, Output, if, for, comunicación entre componentes padres e hijos, servicios, formularios de tipo template driven.

## Puntos Técnicos

Clase Pedido:
```
{
    number: number; // Numero de pedido random de 1 a 1000
    name: string;  // Nombre del cliente
    description: string;  // Descripción del pedido
    date: Date; // Fecha de creación del pedido
}
```

Importante recordar la separación de responsabilidades, quien hace que y como.


## Ejemplo:

![Alt text](image.png)
