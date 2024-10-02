# PODA Alfa-Beta

Este repositorio contiene la implementación de un juego de Tic Tac Toe utilizando el algoritmo de poda alfa-beta para optimizar las decisiones de la computadora. Se proporcionan dos versiones del juego: una con limitaciones en la profundidad de búsqueda y otra sin ellas.

# Archivos del Proyecto

**T8_Limitado.py**: Implementación del juego con un límite de profundidad en el algoritmo minimax. Esta versión busca optimizar el rendimiento al reducir la cantidad de nodos evaluados.
  
**T8_Sin_Limitar.py**: Implementación del juego sin limitaciones en la profundidad. Este archivo utiliza el algoritmo minimax completo, lo que permite a la computadora evaluar todas las posibles jugadas.

# T8_Sin_Limitar.py

Este archivo implementa un juego de Tic Tac Toe en el que el jugador puede competir contra una computadora que utiliza el algoritmo minimax sin restricciones de profundidad. La interfaz gráfica se crea usando Pygame, y el juego permite al jugador "O" competir contra la computadora "X". A continuación se presentan las características clave:

**Interfaz Gráfica**: Utiliza Pygame para mostrar un tablero de Tic Tac Toe.
**Jugabilidad**: El jugador hace clic en una celda para colocar su ficha "O", y la computadora responde con su movimiento.
**Detección de Ganadores**: El juego verifica automáticamente si hay un ganador o si se produce un empate.
**Reinicio Automático**: Al final de cada partida, el tablero se reinicia para comenzar un nuevo juego.

# Tecnologías Usadas

- Python
- Pygame (para la interfaz gráfica)

# Instrucciones para Usar

1. **Clonar el repositorio**:
   ```bash
   git clone <https://github.com/Yesikaa1218/PODA_alfa-beta.git>
   cd poda_alfa_beta
