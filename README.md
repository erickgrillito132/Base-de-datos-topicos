# Base-de-datos-topicos
Tecnológico de Estudios Superiores de Ecatepec (TESE)
**División de Ingeniería en Sistemas Computacionales**

Datos Generales
* **Materia:** Topicos Avanzados de Programación
* **Alumno:** Erick Abraham Arreguin Martínez
* **Proyecto:** Diccionario de Datos, Modelo Entidad Relacional y Modelo Relacional

## Identidad e Imagen Institucional (TESE y TECNM)
El diseño y presentación de este proyecto se apega a la paleta gráfica del TESE:
| **Azul Institucional logo TECNM** | Color principal (Encabezados y estructura) | `#1B365D` | 🟦 |
|**Rojo Institucional logo TESE** | Acento / Engranaje del logotipo | `#C8102E` | 🟥 |
| **Gris Secundario** | Color complementario | `#708090` | ⬛ |
| **Blanco** | Fondo y texto de contraste | `#FFFFFF` | ⬜ |

## 📖 Diccionario de Datos

### Tabla: ALUMNO
| Campo | Tipo de Dato | Longitud | Clave | Nulo | Descripción |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `matricula` | VARCHAR | 10 | **PK** | No Nulo | Número de control del estudiante |
| `nombre` | VARCHAR | 50 | - | No Nulo | Nombre(s) del estudiante |
| `apellido_paterno` | VARCHAR | 50 | - | No Nulo | Apellido paterno |
| `apellido_materno` | VARCHAR | 50 | - | Nulo | Apellido materno |

## 📐 Modelo Entidad - Relación (MER)
*(Puedes subir la foto de tu libreta con "Add file" -> "Upload files")*
![Modelo Entidad Relación](modelo_ER.png)

## 🔗 Modelo Relacional
![Modelo Relacional](modelo_relacional.png)
