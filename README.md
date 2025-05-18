# 📄 Descripción del Dataset: Oferta Académica Virtual en Universidades Argentinas

Este dataset recopila la **oferta académica de carreras virtuales** de universidades argentinas, especialmente centrada en las modalidades a distancia y combinadas, disponibles en distintas instituciones de educación superior del país.

## 🧷 Variables del Dataset

| Columna                         | Descripción |
|---------------------------------|-------------|
| **nombreUniversidad**          | Nombre completo de la universidad que ofrece la carrera. |
| **sector**                     | Sector al que pertenece la institución (Privada o Pública). |
| **provincia**                  | Provincia de la República Argentina donde se encuentra la sede principal de la universidad. |
| **nombreCarrera**              | Nombre oficial de la carrera ofrecida. |
| **areaConocimiento**           | Área disciplinar o campo de conocimiento al que pertenece la carrera. |
| **nivel**                      | Nivel académico de la carrera (Pregrado, Grado, Grado complementario, Maestría, Formación complementaria, etc.). |
| **modalidad**                  | Modalidad de cursado de la carrera (Distancia, Distancia o Combinada). |
| **duracionAnios**              | Duración estimada de la carrera en años o cuatrimestres. |
| **cantidadCarrerasVirtuales** | Número total de carreras virtuales ofrecidas por la universidad. |
| **cantidadAreas**             | Cantidad de áreas de conocimiento cubiertas por la oferta virtual. |
| **porcentajeOfertaVirtual**   | Porcentaje estimado de carreras virtuales sobre el total de la oferta académica de la universidad. (Dato faltante en algunos casos). |
| **observaciones**             | Comentarios o anotaciones adicionales sobre la carrera o la institución. (Frecuentemente vacío). |

## 📌 Ejemplos de Datos

- La **Universidad Católica de La Plata** ofrece múltiples carreras de grado y pregrado a distancia en el área de Humanidades, Ciencias de la Salud y Ciencias Sociales.
- La **Universidad de Palermo** presenta una amplia oferta virtual en el área de negocios, incluyendo carreras de grado como Licenciatura en Marketing, Management o Recursos Humanos, y maestrías como un MBA.

## 🎯 Uso del Dataset

Este dataset puede ser útil para:

- Analizar la expansión de la **educación virtual universitaria en Argentina**.
- Estudiar la **diversidad de áreas de conocimiento** disponibles en modalidad a distancia.
- Comparar la **oferta entre universidades públicas y privadas**.
- Identificar tendencias en niveles académicos más ofrecidos de forma virtual.

## 📝 Observaciones

- Algunas celdas presentan valores faltantes (por ejemplo, en la columna `porcentajeOfertaVirtual`).
- Los valores de duración pueden tener diferentes unidades (años o cuatrimestres), lo cual debe normalizarse para análisis cuantitativos.
