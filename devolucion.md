# Devolución - Examen Recuperatorio
## Control de Versiones con Git y GitHub

**Alumno:** Francisco Payen  
**Repositorio:** https://github.com/FranPayen/recuperatorio-git-payen-francisco  
**Fecha de evaluación:** 13/11/2025

---

## Evaluación por Criterios

### 1. Creación del repositorio remoto - **1/1 pts**
✅ **Cumplido**
- El repositorio fue creado correctamente con el nombre `recuperatorio-git-payen-francisco`
- Se incluye el archivo README.md inicial (confirmado por el commit "Initial commit")
- La configuración remota apunta correctamente a GitHub

**Observaciones:** Perfecto. El repositorio fue creado correctamente con la nomenclatura solicitada.

---

### 2. Clonación y primera modificación - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ El repositorio fue clonado correctamente
- ✅ Se realizó el commit "Modificacion Readme" que actualiza el README.md
- ✅ La información del README incluye correctamente:
  - Título: "# Proyecto de recuperatorio"
  - Descripción del repositorio
  - Materia: Electrónica digital 4
  - Tema: Control de Versiones
  - Año: 2025
- ⚠️ El mensaje del commit fue "Modificacion Readme" en lugar de "Actualizar información del proyecto" como se especificaba en las consignas

**Observaciones:** El contenido es correcto, pero el mensaje del commit no coincide exactamente con lo solicitado en el examen.

---

### 3. Creación de archivo de código - **2.5/3 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se creó la rama `feature-codigo` correctamente
- ✅ Se creó el archivo `programa.py` con la función `saludar()` inicial
- ⚠️ El commit fue "commit codigo" en lugar de "Agregar archivo programa.py" como se solicitaba
- ✅ Se creó el Pull Request #1 que fue fusionado exitosamente a main

**Observaciones:** Bien ejecutado en términos de flujo de trabajo, pero el mensaje del commit no es el especificado en las consignas.

---

### 4. Sincronización y creación de ramas - **2/2 pts**
✅ **Cumplido**
- Se actualizó la rama main local
- Se crearon las ramas `documentacion` y `actualizacion-codigo` (evidenciado por los PRs posteriores)
- El flujo de trabajo demuestra sincronización correcta

**Observaciones:** Correcto. Las ramas fueron creadas y utilizadas según lo solicitado.

---

### 5. Modificación en rama documentación - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se modificó el README.md agregando la sección de documentación
- ✅ Se incluyeron los requisitos (Python 3.x, Git instalado)
- ❌ **La información del autor NO fue completada correctamente:**
  - Nombre: [Tu nombre completo] ← **NO se completó con el nombre real**
  - Fecha: [Fecha actual] ← **NO se completó con la fecha**
- ⚠️ El commit fue "Agregar seccion readme" en lugar de "Agregar sección de documentación"
- ✅ Se creó el Pull Request #2 desde la rama documentacion

**Observaciones:** La estructura está bien, pero faltó completar los datos personales del autor y el mensaje del commit no coincide exactamente.

---

### 6. Modificación en rama actualizacion-codigo - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se modificó el archivo `programa.py` agregando la función `despedir()`
- ✅ Se modificó el README.md (el archivo fue renombrado a "Proyecto de recuperatorio- Version actualizada.md")
- ⚠️ **El cambio del título principal NO se realizó de la manera esperada:** 
  - En lugar de modificar el contenido del README.md existente
  - Se **renombró el archivo** de README.md a "Proyecto de recuperatorio- Version actualizada.md"
  - Esto es técnicamente incorrecto según las consignas
- ⚠️ Los commits fueron "actualizacion codigo y readme" y "actualizacion codigo-readme" en lugar del mensaje especificado "Actualizar programa y README"
- ✅ Se creó el Pull Request #3 desde actualizacion-codigo

**Observaciones:** El alumno renombró el archivo en lugar de modificar su contenido. Aunque la intención es clara, no es la forma correcta de hacer el cambio solicitado. El archivo debió seguir llamándose README.md.

---

### 7. Generación y resolución del conflicto - **2/4 pts**
⚠️ **Parcialmente cumplido**
- ⚠️ Se intentó generar el conflicto esperado entre las ramas documentacion y actualizacion-codigo
- ⚠️ **El conflicto NO se produjo de la manera esperada** debido a que el alumno renombró el archivo README.md en lugar de modificarlo
- ✅ Ambos Pull Requests (#2 y #3) fueron fusionados
- ❌ El resultado final NO es el esperado:
  - El archivo se llama "Proyecto de recuperatorio- Version actualizada.md" en lugar de README.md
  - El contenido NO muestra el título "# Proyecto de recuperatorio - Versión actualizada" como primera línea
  - El título actual es solo "# Proyecto de recuperatorio"
- ✅ El archivo `programa.py` contiene ambas funciones (`saludar()` y `despedir()`)

**Observaciones:** **PROBLEMA SIGNIFICATIVO**: Al renombrar el archivo en lugar de modificar su contenido, el alumno evitó el conflicto que debía resolver. Esto demuestra que no se comprendió correctamente el ejercicio de resolución de conflictos. El archivo debió permanecer como README.md y contener el título "# Proyecto de recuperatorio - Versión actualizada".

---

### 8. Creación de rama hotfix - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se creó la rama `hotfix-typo` correctamente
- ✅ Se modificó el mensaje de la función `saludar()` al texto correcto: "¡Bienvenido al sistema de control de versiones!"
- ⚠️ El commit fue "corregir mensaje de bienvenida" en lugar de "Corregir mensaje de bienvenida" (falta mayúscula inicial)
- ✅ Se creó y fusionó el Pull Request #4

**Observaciones:** Muy bien ejecutado, solo falta el detalle de la mayúscula en el mensaje del commit.

---

### 9. Sincronización final y limpieza - **2/2 pts**
✅ **Cumplido**
- ✅ La rama main local está actualizada
- ✅ Las ramas locales fueron eliminadas (commit "branches-deleted")
- ✅ Solo permanece la rama main en el repositorio local
- ✅ El repositorio está correctamente sincronizado con GitHub

**Observaciones:** Excelente. La limpieza fue realizada correctamente y se eliminaron todas las ramas locales fusionadas.

---

## Resumen de Calificación

| Criterio | Puntaje Obtenido | Puntaje Máximo |
|----------|------------------|----------------|
| 1. Creación del repositorio remoto | 1.0 | 1 |
| 2. Clonación y primera modificación | 1.5 | 2 |
| 3. Creación de archivo de código | 2.5 | 3 |
| 4. Sincronización y creación de ramas | 2.0 | 2 |
| 5. Modificación en rama documentación | 1.5 | 2 |
| 6. Modificación en rama actualizacion-codigo | 1.5 | 2 |
| 7. Generación y resolución del conflicto | 2.0 | 4 |
| 8. Creación de rama hotfix | 1.5 | 2 |
| 9. Sincronización final y limpieza | 2.0 | 2 |

**CALIFICACIÓN FINAL: 15.5/20 puntos**

---

## Comentarios Generales

El alumno demostró un **buen manejo general de Git y GitHub**, completando todas las etapas del examen. Sin embargo, presenta algunas áreas de mejora importantes.

**Fortalezas:**
- ✅ Comprensión del flujo de trabajo básico con ramas
- ✅ Creación y manejo apropiado de Pull Requests (4 PRs creados y fusionados)
- ✅ Sincronización correcta entre repositorio local y remoto
- ✅ Implementación completa de la limpieza final
- ✅ Estructura general del trabajo correcta
- ✅ Todos los archivos finales contienen las funciones y secciones esperadas

**Áreas de mejora:**

1. **Mensajes de commits (múltiples etapas):**
   - Los mensajes de commit no coinciden exactamente con los especificados en las consignas
   - Es importante seguir las especificaciones exactas en un examen
   - Ejemplos: "Modificacion Readme" vs "Actualizar información del proyecto"

2. **Etapa 5 - Documentación del autor (0.5 pts):**
   - No se completaron los datos personales del autor
   - Los campos quedaron como "[Tu nombre completo]" y "[Fecha actual]"
   - Es importante completar toda la información solicitada

3. **Etapa 6 - Modificación de README (0.5 pts perdidos):**
   - **PROBLEMA CONCEPTUAL**: Se renombró el archivo README.md en lugar de modificar su contenido
   - El archivo debió seguir llamándose README.md
   - Esto afectó la etapa siguiente de resolución de conflictos

4. **Etapa 7 - Resolución del conflicto (2 pts perdidos):**
   - **PROBLEMA CRÍTICO**: Al renombrar el archivo, se evitó el conflicto que debía resolverse
   - El ejercicio perdió su propósito pedagógico principal: aprender a resolver conflictos
   - El resultado final no cumple con lo esperado:
     - El archivo no se llama README.md
     - El título no es el especificado

**Análisis del problema principal:**

La decisión de **renombrar el archivo** en lugar de **modificar su contenido** causó un efecto en cadena:
- Git interpretó esto como la creación de un nuevo archivo
- No se generó el conflicto esperado en la etapa 7
- El alumno no pudo practicar la resolución de conflictos reales
- El resultado final no coincide con las especificaciones

**Recomendaciones:**
1. Leer cuidadosamente las consignas y seguir las especificaciones exactas
2. Usar los mensajes de commit exactos cuando se especifican
3. Completar todos los campos de información solicitados
4. Entender la diferencia entre:
   - Modificar el contenido de un archivo
   - Renombrar un archivo
5. Practicar la resolución de conflictos en Git cuando múltiples ramas modifican el mismo archivo

---

## Conclusión

El trabajo demuestra **comprensión sólida de los fundamentos de Git y GitHub**, con un flujo de trabajo generalmente correcto. El alumno completó todas las etapas y demostró capacidad para trabajar con ramas, pull requests y sincronización.

Los puntos perdidos se deben principalmente a:
- Falta de atención a los detalles específicos (mensajes de commit, datos del autor)
- Un error conceptual importante al renombrar el archivo en lugar de modificarlo, lo que impidió la práctica de resolución de conflictos

**Estado: APROBADO (15.5/20)**

El alumno ha demostrado competencia en el manejo de Git y GitHub. Se recomienda revisar los conceptos de resolución de conflictos y prestar más atención a seguir las especificaciones exactas de las consignas.

---

## Detalle de Archivos Finales

**Archivo esperado:** README.md  
**Archivo encontrado:** "Proyecto de recuperatorio- Version actualizada.md"

**Contenido del archivo:**
- ✅ Título "# Proyecto de recuperatorio" presente
- ❌ Falta el título modificado "# Proyecto de recuperatorio - Versión actualizada" como primera línea
- ✅ Información del proyecto completa (Materia, Tema, Año)
- ✅ Sección de Documentación presente
- ✅ Requisitos listados correctamente
- ❌ Datos del autor sin completar

**Archivo programa.py:**
- ✅ Función `saludar()` con mensaje correcto: "¡Bienvenido al sistema de control de versiones!"
- ✅ Función `despedir()` con mensaje: "Hasta pronto!"
- ✅ Bloque `if __name__ == "__main__":` presente
- ✅ Ambas funciones siendo llamadas correctamente
