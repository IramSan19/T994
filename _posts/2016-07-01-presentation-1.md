---
title: Investigación sobre Actuadores en Sistemas Programables
layout: post
permalink: /actuadores/
background: '#f0f0f0'

slides:
 - title: Actuadores Eléctricos
   slide-data: |
     Los actuadores eléctricos son dispositivos que convierten energía eléctrica en energía mecánica. Existen varios tipos, entre los que destacan:
     - **Motores eléctricos**: Transforman la energía eléctrica en movimiento rotativo.
     - **Solenoides**: Proporcionan movimiento lineal al ser energizados.
     - **Servomotores**: Controlan la posición angular con alta precisión.
     - **Actuadores piezoeléctricos**: Usan la deformación de materiales piezoeléctricos para producir movimiento.
  
 - title: Funcionamiento de Actuadores Eléctricos
   slide-data: |
     Los actuadores eléctricos funcionan mediante la interacción entre campos electromagnéticos y componentes mecánicos. Ejemplos:
     - **Motores eléctricos**: Rotación de un rotor en un campo magnético.
     - **Solenoides**: Creación de un campo magnético que mueve un núcleo.
     - **Servomotores**: Control de retroalimentación para ajustar la posición.

 - title: Características de Actuadores Eléctricos
   slide-data: |
     Las características incluyen:
     - **Velocidad**: Capacidad de respuesta y rapidez en el movimiento.
     - **Precisión**: Exactitud en la posición o el movimiento.
     - **Torque**: Fuerza ejercida.
     - **Consumo energético**: Eficiencia energética.
     - **Tamaño**: Dimensiones y peso.

 - title: Modo de Comunicación de Actuadores Eléctricos
   slide-data: |
     Se comunican mediante:
     - **Protocolos de comunicación**: Modbus, CAN bus, Ethernet/IP.
     - **Señales de control**: Voltajes o pulsos de ancho variable (PWM).

 - title: Actuadores Mecánicos
   slide-data: |
     Utilizan componentes mecánicos para generar movimiento. Tipos comunes:
     - **Levas**: Movimiento rotativo a lineal.
     - **Engranajes**: Transmiten movimiento y fuerza.
     - **Cadenas y poleas**: Transmiten fuerza a distancias mayores.

 - title: Funcionamiento de Actuadores Mecánicos
   slide-data: |
     Conversión de un tipo de movimiento en otro. Ejemplos:
     - **Levas**: Empujan un puntero al girar.
     - **Engranajes**: Rotación de un engranaje mueve a otro.

 - title: Características de Actuadores Mecánicos
   slide-data: |
     Incluyen:
     - **Durabilidad**: Resistencia al desgaste.
     - **Capacidad de carga**: Fuerza soportada.
     - **Reversibilidad**: Posibilidad de revertir movimiento.
     - **Mantenimiento**: Necesidades de lubricación.

 - title: Actuadores Hidráulicos
   slide-data: |
     Utilizan fluidos para generar movimiento. Tipos comunes:
     - **Cilindros hidráulicos**: Movimiento lineal.
     - **Motores hidráulicos**: Movimiento rotativo.
     - **Bombas hidráulicas**: Generan flujo de fluido.

 - title: Funcionamiento de Actuadores Hidráulicos
   slide-data: |
     Basado en el principio de Pascal, donde la presión se transmite uniformemente. Ejemplos:
     - **Cilindros hidráulicos**: Aumento de presión desplaza un vástago.
     - **Motores hidráulicos**: Utilizan presión para girar un rotor.

 - title: Características de Actuadores Hidráulicos
   slide-data: |
     Incluyen:
     - **Fuerza**: Generación de altas fuerzas.
     - **Control**: Precisión en el control de movimientos.
     - **Flexibilidad**: Operación en entornos difíciles.

 - title: Modo de Comunicación de Actuadores Hidráulicos
   slide-data: |
     Se comunican a través de:
     - **Válvulas de control**: Regulación de flujo y presión.
     - **Sensores de presión**: Monitoreo del sistema hidráulico.

---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
  <h1>{{slide.title}}</h1>
  {{ slide.slide-data }}
</section>
{% endfor %}
