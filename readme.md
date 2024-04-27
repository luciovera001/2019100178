# EP1 - Proyecto de Sistemas Inteligentes

Este proyecto es del Examen Parcial 1 de la Materia Proyecto de Ssitemas Inteligentes. El script `turtle_movement.py` permite controlar el movimiento de la tortuga en el entorno de ROS.

## Requisitos

- ROS Melodic
- Python 3
- Git (para clonar el repositorio)

## Configuración del entorno

Pasos para configurar el entorno:

### Clonar el repositorio

En primer lugar, clonar este repositorio en el espacio de trabajo de ROS. Abrir la terminal y ejecutar:

```bash
//El nombre del workspace puede ser distinto al de este eaxmen
cd Lucio Vera/src
git clone https://github.com/luciovera001/2019100178.git
cd ..
catkin_make
```
## Ejecución del script

Pasos para ejecutar el script

### Iniciar el ROS Core
```bash
roscore
```

### Ejecutar el nodo Turtlesim
En otra terminal, inicia el simulador turtle:

```bash
rosrun turtlesim turtlesim_node
```

### Correr el script `turtle_movement.py`

En una nueva terminal y navega al directorio del script:

```bash
cd Lucio Vera/src/turtle_unida/src
python turtle_movement.py
```

Con estos pasos, la tortuga en el simulador ROS estará en constante movimiento circular.

## About me
Lucio Vera - 2019100178 - UNIDA | 9no Semestre
