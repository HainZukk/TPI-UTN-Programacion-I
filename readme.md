# Los Cinco Demonios
### Trabajo Práctico Integrador — Programación I | UTN

Un juego de consola desarrollado en **C++** donde el jugador debe sellar a cinco demonios usando el poder de los dados antes de que se acaben los intentos.

---

## 📖 Historia

Una antigua maldición ha liberado a cinco demonios oscuros, cada uno ligado a un elemento de las sombras. Como el último descendiente del linaje elegido, deberás invocar los sigilos correctos tirando los dados para sellarlos uno a uno. ¿Tendrás el coraje y la suerte suficiente?

---

## 🎮 Mecánicas del juego

- El jugador tiene un número limitado de **tiradas de dados**.
- Cada tirada puede habilitar o deshabilitar opciones para sellar demonios.
- Los demonios están asociados a **elementos de las sombras**; la combinación de los dados determina cuáles pueden ser sellados en cada turno.
- El juego cuenta con un **evento especial** (`lazamanus`) que puede alterar el curso de la partida.
- Al finalizar, se pueden consultar **estadísticas** de victorias, derrotas e invocaciones.

---

## Estructura del proyecto

```

```

---

## Compilación y ejecución

### Requisitos
- Compilador C++ compatible con C++11 o superior (g++, MinGW, MSVC, etc.)

### Compilar

```bash
g++ main.cpp funciones.cpp -o juego
```

---

## 🧩 Funciones principales

| Función | Descripción |
|---|---|
| `menuPrincipal()` | Muestra el menú principal del juego |
| `jugar()` | Controla el flujo principal de una partida |
| `tirarDado()` | Genera el resultado de una tirada |
| `EvaluarTirada()` | Determina qué demonios pueden sellarse según el dado |
| `elegirDemonio()` | El jugador elige qué demonio sellar |
| `ganar()` / `derrota()` | Gestionan el fin de partida |
| `estadisticas()` | Muestra victorias, derrotas e invocaciones |
| `lore()` | Narra la historia introductoria |
| `creditos()` | Muestra los créditos del equipo |

---

## 👥 Integrantes — Rodriguez Paula , Nguyen Tobias.

Trabajo desarrollado en grupo para la materia **Programación I** de la **Universidad Tecnológica Nacional (UTN)**.

---

## 📌 Notas

- El proyecto fue desarrollado con fines académicos.