# Nicolas_Jimenez_5º_Prueba_de_Evaluacion_Continua2023_2024
 https://github.com/NicolasJRuax/Nicolas_Jimenez_5-_Prueba_de_Evaluacion_Continua2023_2024
# Proyecto de Ejercicio 1

Este proyecto contiene implementaciones de varios patrones de diseño en Java.

## Estructura del proyecto

El proyecto está estructurado en diferentes entregas, cada una con su respectivo paquete y clases.

### Entrega 1

#### Paquete: com.examen.Ejercicio1.Entrega1.Factory

Este paquete contiene implementaciones del patrón Factory.

- `Restaurante`: Interfaz para los restaurantes.
- `RestauranteDeLujo`: Clase que implementa `Restaurante` para un restaurante de lujo.
- `RestauranteFactory`: Clase factory para crear diferentes tipos de restaurantes.
- `RestauranteRapido`, `RestauranteTematico`: Implementaciones de restaurantes.

#### Paquete: com.examen.Ejercicio1.Entrega1.Singleton

Este paquete contiene una implementación del patrón Singleton.

- `GestorRestaurantes`: Clase singleton para gestionar restaurantes.

#### Paquete: com.examen.Ejercicio1.Entrega1.Strategy

Este paquete contiene implementaciones del patrón Strategy.

- `EstrategiaServicio`: Interfaz para las estrategias de servicio.
- `ServicioDeLujo`, `ServicioRapido`, `ServicioTematico`: Implementaciones de estrategias de servicio.

### Entrega 2

#### Paquete: com.examen.Ejercicio1.Entrega2.Adapter

Este paquete contiene una implementación del patrón Adapter.

- `AdaptadorSistemaReserva`: Clase para adaptar un sistema antiguo de reserva.
- `SistemaReserva`, `SistemaReservaAntiguo`: Interfaz y clase del sistema externo de reserva.

#### Paquete: com.examen.Ejercicio1.Entrega2.Composite

Este paquete contiene una implementación del patrón Composite.

- `ComponenteRestaurante`: Interfaz para los componentes de los restaurantes.
- `GrupoRestaurantes`: Implementación de grupo de restaurantes (Composite).
- `RestauranteIndividual`: Implementación de un restaurante individual.

#### Paquete: com.examen.Ejercicio1.Entrega2.Observer

Este paquete contiene una implementación del patrón Observer.

- `Cliente`, `Observador`: Clases para el cliente y la interfaz de observador.
- `SujetoObservado`: Clase sujeto observado.

### Entrega 3

#### Paquete: com.examen.Ejercicio1.Entrega3.Command

Este paquete contiene implementaciones del patrón Command.

- `Cocina`: Clase para representar la cocina del restaurante.
- `ComandoCancelacion`, `ComandoOrden`, `ComandoReserva`: Implementaciones de comandos.

#### Paquete: com.examen.Ejercicio1.Entrega3.Mediator

Este paquete contiene una implementación del patrón Mediator.

- `Entrega`, `ServicioCliente`: Clases para representar los servicios de entrega y cliente.
- `MediadorRestaurante`: Mediador para facilitar la comunicación entre los componentes del restaurante.

### Entrega 4

#### Paquete: com.examen.Ejercicio1.Entrega4.Composite

Este paquete contiene una implementación del patrón Composite.

- `ComponenteRestaurante`: Interfaz para los componentes de los restaurantes.
- `GrupoRestaurantes`: Implementación de grupo de restaurantes (Composite).
- `RestauranteIndividual`: Implementación de un restaurante individual.

#### Paquete: com.examen.Ejercicio1.Entrega4.MVC

Este paquete contiene una implementación del patrón MVC.

- `ControladorRestaurante`: Clase controlador.
- `ModeloRestaurante`: Clase modelo.
- `VistaRestaurante`: Clase vista.


