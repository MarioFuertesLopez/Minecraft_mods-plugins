# Guía de Contribución

Gracias por tu interés en contribuir a este repositorio de mods de Minecraft. Este documento establece las directrices y el proceso para realizar contribuciones de forma ordenada y efectiva.

## Tabla de contenidos

- [Código de conducta](#código-de-conducta)
- [Cómo contribuir](#cómo-contribuir)
- [Proceso de Pull Request](#proceso-de-pull-request)
- [Estructura de carpetas](#estructura-de-carpetas)
- [Estándares de commits](#estándares-de-commits)
- [Requisitos para mods](#requisitos-para-mods)
- [Reportar errores](#reportar-errores)

---

## Código de conducta

Este proyecto se compromete a proporcionar un ambiente acogedor y libre de acoso para todos. Esperamos que los colaboradores:

- Sean respetuosos con otros colaboradores
- Acepten críticas constructivas
- Se enfoquen en lo que es mejor para la comunidad
- Muestren empatía hacia otros miembros

---

## Cómo contribuir

### Antes de empezar

1. Revisa los Issues existentes para ver si alguien ya está trabajando en algo similar
2. Si no existe un Issue relacionado, crea uno describiendo tu propuesta
3. Espera comentarios antes de comenzar cambios significativos

### Tipos de contribuciones

Este repositorio acepta las siguientes contribuciones:

**Añadir nuevos mods:**
- Mods populares y estables
- Mods que mejoren la experiencia de usuarios novatos
- Mods compatibles con las versiones soportadas

**Mejorar documentación:**
- Correcciones de errores tipográficos
- Aclaraciones en instrucciones
- Traducciones
- Añadir ejemplos o capturas de pantalla

**Reportar problemas:**
- Mods incompatibles
- Enlaces rotos
- Errores en la documentación

---

## Proceso de Pull Request

### 1. Fork y clonación

```bash
# Fork el repositorio desde GitHub
# Luego clona tu fork
git clone https://github.com/TU_USUARIO/Minecraft_mods-plugins.git
cd Minecraft_mods-plugins
```

### 2. Crear una rama

Crea una rama descriptiva para tus cambios:

```bash
git checkout -b feature/nombre-descriptivo
```

Ejemplos de nombres de rama:
- `feature/add-sodium-fabric`
- `feature/update-installation-guide`
- `fix/broken-curseforge-links`
- `docs/improve-readme`

### 3. Realizar cambios

- Añade los archivos en la carpeta correspondiente
- Actualiza el README.md de la subcarpeta si añades mods
- Asegúrate de seguir la estructura establecida

### 4. Commit

Realiza commits atómicos con mensajes descriptivos:

```bash
git add .
git commit -m "[Categoría] Descripción breve del cambio"
```

Ver sección de [Estándares de commits](#estándares-de-commits) para más detalles.

### 5. Push a tu fork

```bash
git push origin feature/nombre-descriptivo
```

### 6. Crear Pull Request

1. Ve a tu fork en GitHub
2. Haz clic en "Compare & pull request"
3. Completa la plantilla de Pull Request:
   - Descripción clara de los cambios
   - Referencias a Issues relacionados si existen
   - Lista de mods añadidos o cambios realizados
4. Espera la revisión de los mantenedores

### 7. Revisión

Los mantenedores revisarán tu PR y pueden:
- Aprobarlo y hacer merge
- Solicitar cambios
- Hacer comentarios o preguntas

Responde a los comentarios y realiza los cambios solicitados.

---

## Estructura de carpetas

Respeta la siguiente estructura al añadir mods:

```
Java/
├── Vanilla/[Versión]/
├── Fabric/[Versión]/
├── NeoForge/[Versión]/
└── Shaders/[Rango de versiones]/
```

**Reglas:**
- Coloca cada mod en la carpeta correspondiente a su loader y versión exacta
- Nombra los archivos claramente: `nombre-mod-version.jar`
- Actualiza el README.md de esa carpeta con la información del mod

---

## Estándares de commits

Utiliza el siguiente formato para los mensajes de commit:

```
[Categoría] Descripción breve (máximo 72 caracteres)

Descripción detallada opcional explicando:
- Qué cambios se hicieron
- Por qué fueron necesarios
- Referencias a Issues si aplica
```

**Categorías:**
- `[Mods]` - Añadir o actualizar mods
- `[Docs]` - Cambios en documentación
- `[Fix]` - Correcciones de errores
- `[Structure]` - Cambios en estructura de carpetas
- `[Chore]` - Tareas de mantenimiento

**Ejemplos:**

```bash
git commit -m "[Mods] Añadir Sodium 0.5.8 para Fabric 1.20"

git commit -m "[Docs] Actualizar guía de instalación con capturas"

git commit -m "[Fix] Corregir enlace roto a CurseForge en README"
```

**Buenas prácticas:**
- Mensajes en imperativo: "Añadir" no "Añadido"
- Específicos y descriptivos
- Un commit por cambio lógico
- Referencias a Issues: `Fix #15: Corregir estructura de carpetas`

---

## Requisitos para mods

Antes de añadir un mod, asegúrate de que cumple con:

### Requisitos obligatorios

**Origen legítimo:**
- Descargado de fuentes oficiales: CurseForge, Modrinth, sitio web oficial del autor
- No subir mods pirateados o redistribuidos ilegalmente

**Compatibilidad:**
- Versión exacta de Minecraft especificada
- Compatible con el loader indicado (Fabric/NeoForge)
- Sin conflictos conocidos con mods comunes

**Seguridad:**
- Sin malware o código malicioso
- Revisado por la comunidad en plataformas oficiales

**Licencia:**
- Permitida la redistribución según la licencia del mod
- Incluir archivo LICENSE si el mod lo requiere

### Información requerida

Al añadir un mod, actualiza el README.md de la carpeta con:

```markdown
## Nombre del Mod

**Versión:** X.X.X
**Descripción:** Breve descripción de qué hace el mod
**Autor:** Nombre del autor original
**Fuente:** [Enlace a CurseForge/Modrinth]
**Dependencias:** Lista de mods requeridos (si aplica)
```

### Mods no aceptados

No se aceptarán mods que:
- Contengan malware o sean sospechosos
- Violen derechos de autor
- Sean versiones no oficiales o modificadas sin permiso
- Estén obsoletos o abandonados sin alternativas
- Causen conflictos graves con mods populares

---

## Reportar errores

Si encuentras un problema, crea un Issue con la siguiente información:

**Para bugs:**
- Descripción clara del problema
- Pasos para reproducir el error
- Comportamiento esperado vs. comportamiento actual
- Versión de Minecraft y loader afectados
- Capturas de pantalla si es relevante

**Para solicitudes de mods:**
- Nombre del mod
- Por qué debería incluirse
- Versiones soportadas
- Enlace a la fuente oficial

**Plantilla de Issue:**

```markdown
**Tipo:** [Bug / Solicitud de mod / Mejora de documentación]

**Descripción:**
[Descripción detallada]

**Versión afectada:**
[Minecraft X.XX.X con Fabric/NeoForge]

**Pasos para reproducir (si es un bug):**
1. Paso 1
2. Paso 2
3. ...

**Comportamiento esperado:**
[Qué debería pasar]

**Comportamiento actual:**
[Qué pasa realmente]
```

---

## Revisión y aprobación

### Proceso de revisión

Todos los Pull Requests pasan por revisión antes de ser aceptados:

1. **Revisión técnica:** Verificar estructura correcta y archivos apropiados
2. **Revisión de seguridad:** Confirmar origen legítimo del mod
3. **Revisión de documentación:** Verificar que el README esté actualizado
4. **Pruebas:** Comprobar compatibilidad y funcionamiento

### Tiempo de respuesta

- Pull Requests simples: 1-3 días
- Pull Requests complejos: 3-7 días
- Issues: 1-5 días

Los mantenedores revisan las contribuciones diariamente. La paciencia es apreciada.

### Criterios de aprobación

Un PR será aprobado si:
- Sigue las directrices de este documento
- Pasa todas las revisiones
- No introduce errores o conflictos
- La documentación está actualizada

---

## Contacto

Si tienes preguntas sobre el proceso de contribución:

- Abre un Issue con la etiqueta `question`
- Consulta Issues existentes por si tu duda ya fue respondida
- Revisa el README.md principal para información general

---

## Licencia

Al contribuir a este repositorio, aceptas que tus contribuciones sean licenciadas bajo la licencia MIT del proyecto.

---

**Gracias por contribuir y ayudar a mejorar este repositorio para la comunidad de Minecraft.**
