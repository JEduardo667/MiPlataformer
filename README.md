# SODVI — Plataformer 2D en Pixel Art
## RAMA main

Repositorio del proyecto de videojuego desarrollado por **SODVI (Sociedad de Videojuegos)**.

## Información del proyecto

| Campo | Detalle |
|---|---|
| Equipo | SODVI (Sociedad de Videojuegos) |
| Nivel | 2 |
| Tipo de juego | Plataformer |
| Estilo de arte | Pixel art |
| Motor | Unity 6.3 LTS |
| Versión del editor | `6000.3.9f1` |

## Integrantes

| Nombre | Rol |
|---|---|
| _Por definir_ | Coder/Programador |
| _Por definir_ | Artista |
| _Por definir_ | Musico |
| _Por definir_ | Escritor |
| José Eduardo Martínez García | Proyect Manager |



## Requisitos

- [Unity Hub](https://unity.com/download)
- Unity Editor **6000.3.9f1** (LTS). Todo el equipo debe usar exactamente esta versión.
- Git y GitHub Desktop (o cualquier cliente de Git)
- Editor de código: Visual Studio, VS Code o Rider

## Cómo abrir el proyecto

1. Clona el repositorio:
   - En GitHub Desktop: **File → Clone repository** y selecciona este repositorio.
   - Por terminal: `git clone <URL-del-repositorio>`
2. Cambia a la rama `develop`.
3. En Unity Hub: **Add → Add project from disk** y selecciona la carpeta clonada.
4. Si Unity Hub solicita instalar la versión del editor, instala `6000.3.9f1`.
5. Si Unity pregunta si desea actualizar el proyecto a otra versión, selecciona **Cancelar**.
6. La primera apertura puede tardar varios minutos mientras Unity regenera la carpeta `Library/`.

## Flujo de trabajo con Git

| Rama | Propósito |
|---|---|
| `main` | Versión estable del proyecto. Solo se actualiza en hitos o al final del desarrollo. |
| `develop` | Rama de integración del trabajo del equipo. |
| `feature/<nombre>` | Ramas de trabajo individuales para cada función. Se integran a `develop`. |

**Convenciones**

- No se hacen commits directos a `main`.
- Cada tarea se desarrolla en una rama `feature/` creada desde `develop`, por ejemplo `feature/movimiento-jugador` o `feature/nivel-1`.
- La integración a `develop` se realiza mediante Pull Request.
- Antes de comenzar a trabajar, actualizar la rama con los cambios de `develop`.
- Los mensajes de commit deben ser claros y breves, por ejemplo: `Agrega salto del jugador`.