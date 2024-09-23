---
# Investigación sobre Actuadores en Sistemas Programables

## 2.1 Actuadores Eléctricos

### 2.1.1 Tipos
Los actuadores eléctricos son dispositivos que convierten energía eléctrica en energía mecánica. Existen varios tipos, entre los que destacan:

- **Motores eléctricos**: Transforman la energía eléctrica en movimiento rotativo.
- **Solenoides**: Proporcionan movimiento lineal al ser energizados.
- **Servomotores**: Controlan la posición angular con alta precisión.
- **Actuadores piezoeléctricos**: Usan la deformación de materiales piezoeléctricos para producir movimiento.

### 2.1.2 Funcionamiento
Los actuadores eléctricos funcionan mediante la interacción entre campos electromagnéticos y componentes mecánicos. Por ejemplo:

- **Motores eléctricos**: Funcionan mediante la rotación de un rotor dentro de un campo magnético, lo que genera un movimiento.
- **Solenoides**: Cuando se aplica corriente, se crea un campo magnético que mueve un núcleo dentro de un cilindro.
- **Servomotores**: Utilizan un controlador de retroalimentación para ajustar la posición del motor.

### 2.1.3 Características
Las características de los actuadores eléctricos incluyen:

- **Velocidad**: Capacidad de respuesta y rapidez en el movimiento.
- **Precisión**: Exactitud en la posición o el movimiento.
- **Torque**: Fuerza que pueden ejercer.
- **Consumo energético**: Eficiencia energética en su operación.
- **Tamaño**: Dimensiones y peso que pueden influir en su aplicación.

### 2.1.4 Modo de Comunicación
Los actuadores eléctricos se comunican principalmente mediante:

- **Protocolos de comunicación**: Como Modbus, CAN bus, y Ethernet/IP, que permiten el control y monitoreo.
- **Señales de control**: A través de voltajes o pulsos de ancho variable (PWM) que ajustan su operación.

## 2.2 Actuadores Mecánicos

### 2.2.1 Tipos
Los actuadores mecánicos utilizan componentes mecánicos para generar movimiento. Tipos comunes incluyen:

- **Levas**: Transforman movimiento rotativo en movimiento lineal.
- **Engranajes**: Transmiten movimiento y fuerza entre ejes.
- **Cadenas y poleas**: Transmiten fuerza y movimiento a distancias mayores.

### 2.2.2 Funcionamiento
Los actuadores mecánicos funcionan mediante la conversión de un tipo de movimiento en otro. Por ejemplo:

- **Levas**: Al girar, la leva empuja un puntero, generando movimiento lineal.
- **Engranajes**: La rotación de un engranaje mueve a otro engranaje, aumentando o disminuyendo la velocidad y torque.

### 2.2.3 Características
Entre las características de los actuadores mecánicos se incluyen:

- **Durabilidad**: Resistencia al desgaste y la fatiga.
- **Capacidad de carga**: Máxima fuerza que pueden soportar.
- **Reversibilidad**: Posibilidad de revertir el movimiento.
- **Mantenimiento**: Necesidades de lubricación y reparación.

### 2.2.4 Modo de Comunicación
Los actuadores mecánicos generalmente operan sin un modo de comunicación electrónico, aunque pueden ser controlados mediante:

- **Mecanismos manuales**: Como palancas o manivelas.
- **Controles automáticos**: Que activan o desactivan el mecanismo.

## 2.3 Actuadores Hidráulicos

### 2.3.1 Tipos
Los actuadores hidráulicos utilizan fluidos para generar movimiento. Tipos comunes son:

- **Cilindros hidráulicos**: Producen movimiento lineal.
- **Motores hidráulicos**: Transforman la presión del fluido en movimiento rotativo.
- **Bombas hidráulicas**: Generan el flujo de fluido que permite el movimiento.

### 2.3.2 Funcionamiento
Los actuadores hidráulicos funcionan según el principio de Pascal, donde la presión aplicada en un fluido se transmite uniformemente. Por ejemplo:

- **Cilindros hidráulicos**: Al aumentar la presión del fluido en un extremo del cilindro, se desplaza un vástago.
- **Motores hidráulicos**: Utilizan la presión del fluido para girar un rotor.

### 2.3.3 Características
Las características de los actuadores hidráulicos incluyen:

- **Fuerza**: Capacidad para generar altas fuerzas a través de fluidos.
- **Control**: Precisión en el control de movimientos debido a la incomprensibilidad del fluido.
- **Flexibilidad**: Capacidad para operar en entornos difíciles.

### 2.3.4 Modo de Comunicación
Los actuadores hidráulicos se comunican principalmente a través de:

- **Válvulas de control**: Que regulan el flujo y la presión del fluido.
- **Sensores de presión**: Que monitorean el estado del sistema hidráulico.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
