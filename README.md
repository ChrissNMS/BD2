# 🏰 Generador de Dungeon — Tarea I (Base de Datos II)

Proyecto desarrollado para la **Tarea I** de la asignatura **Base de Datos II**.  
El objetivo es implementar un generador de mapas de tipo *Dungeon* con clases bien estructuradas,  
contenidos aleatorios (monstruos, tesoros, eventos, jefes), serialización y visualización.

---

## ⚙️ **Cómo ejecutar el proyecto**

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/BD2.git
   cd BD2

2. Crear el entorno virtual e instalar dependencias (con uv):

uv sync


3. Ejecutar el programa principal:

uv run python main.py


4. El programa generará automáticamente un mapa aleatorio y guardará la partida en:

partida.json


## ✅ Cumplimiento de requerimientos

1	Clase Habitacion	✅	Implementada en core.py
2	Clase Mapa	✅	Genera estructura, conexiones y contenido
3	Clase Objeto	✅	Usa dataclass
4	Clase Explorador	✅	Movimiento, combate y exploración
5	Clase abstracta ContenidoHabitacion	✅	Uso correcto de ABC
6	Clases Tesoro, Monstruo, Jefe	✅	Implementadas con interacciones
7	Estadísticas del mapa	✅	Método obtener_estadisticas_mapa()
8	Serialización JSON/YAML	✅	Función guardar_partida()
9	Visualización con rich	✅	Clase Visualizador
10	Eventos aleatorios	✅	Clase Evento con efectos
11	Dificultad escalable	✅	Función ajustar_dificultad()

## 🧩 Notas adicionales

- El proyecto fue inicializado utilizando uv.

- Código completamente documentado y organizado según los requerimientos de la Tarea I.

- Compatible con sistemas operativos Windows, Linux y macOS.

- Los colores del mapa son generados con la librería rich.

## 👨‍💻 Autor

Nombre: Christofer Gutiérrez
Asignatura: Base de Datos II
Profesor: Diego Álvarez S.
Año: 2025
