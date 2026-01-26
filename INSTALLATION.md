# Guía de instalación de mods

Esta guía te ayudará a instalar mods de Minecraft paso a paso.

## Requisitos previos

Antes de instalar mods, necesitas:
- Minecraft Java Edition instalado
- Un loader de mods instalado (Fabric o NeoForge)
- Conocer tu versión exacta de Minecraft

---

## Paso 1: Instalar un loader de mods

### Opción A: Fabric Loader

1. Ve a https://fabricmc.net/use/installer/
2. Descarga el instalador de Fabric
3. Ejecuta el archivo descargado
4. Selecciona la versión de Minecraft que usas
5. Haz clic en "Install"
6. Abre Minecraft Launcher y selecciona el perfil "fabric-loader"

### Opción B: NeoForge

1. Ve a https://neoforged.net/
2. Descarga el instalador para tu versión de Minecraft
3. Ejecuta el archivo descargado
4. Selecciona "Install client"
5. Haz clic en "OK"
6. Abre Minecraft Launcher y selecciona el perfil "NeoForge"

---

## Paso 2: Localizar tu carpeta de Minecraft

### Windows

1. Presiona `Windows + R`
2. Escribe `%appdata%/.minecraft`
3. Pulsa Enter

### Mac

1. Abre Finder
2. Presiona `Cmd + Shift + G`
3. Escribe `~/Library/Application Support/minecraft`
4. Pulsa Enter

### Linux

1. Abre el explorador de archivos
2. Ve a `~/.minecraft`
3. Si no ves carpetas ocultas, presiona `Ctrl + H`

---

## Paso 3: Crear carpeta de mods

1. Dentro de la carpeta `.minecraft`, busca la carpeta `mods`
2. Si no existe, créala manualmente
3. Esta carpeta es donde irán todos los mods

---

## Paso 4: Descargar mods desde este repositorio

1. Navega a la carpeta correspondiente a tu loader y versión
   - Ejemplo: `Java/Fabric/1.20/` si usas Fabric en Minecraft 1.20
2. Descarga los archivos .jar que quieras
3. Guárdalos en tu ordenador

---

## Paso 5: Instalar los mods

1. Copia los archivos .jar descargados
2. Pégalos en la carpeta `mods` que creaste en el Paso 3
3. Cierra Minecraft si está abierto

---

## Paso 6: Iniciar Minecraft con mods

1. Abre Minecraft Launcher
2. Selecciona el perfil correspondiente:
   - Para Fabric: perfil "fabric-loader"
   - Para NeoForge: perfil "NeoForge"
3. Haz clic en "JUGAR"
4. Los mods se cargarán automáticamente

---

## Verificar que los mods funcionan

### Con Fabric

1. En el menú principal, busca el botón "Mods"
2. Haz clic y verás la lista de mods cargados

### Con NeoForge

1. En el menú principal, busca el botón "Mods"
2. Haz clic y verás la lista de mods cargados

---

## Solución de problemas comunes

### El juego no inicia

**Causas comunes:**
- Versión incorrecta del mod (verifica que coincida con tu Minecraft)
- Mod incompatible con el loader (Fabric vs NeoForge)
- Falta una dependencia requerida por el mod

**Solución:**
1. Elimina el último mod que instalaste
2. Verifica la versión correcta en el README del repositorio
3. Lee las dependencias requeridas

### El botón "Mods" no aparece

**Causa:**
- El loader no está instalado correctamente

**Solución:**
1. Reinstala Fabric o NeoForge
2. Asegúrate de seleccionar el perfil correcto en el launcher

### Crash al iniciar

**Causa:**
- Conflicto entre mods

**Solución:**
1. Elimina todos los mods
2. Añádelos uno por uno para identificar cuál causa el problema
3. Consulta el README del mod para ver incompatibilidades conocidas

### Rendimiento bajo

**Solución:**
1. Instala mods de optimización como Sodium o Lithium (Fabric)
2. Reduce la configuración gráfica en opciones de Minecraft
3. Cierra otros programas mientras juegas

---

## Desinstalar mods

Para desinstalar un mod:
1. Ve a la carpeta `mods`
2. Elimina el archivo .jar del mod que quieres quitar
3. Reinicia Minecraft

---

## Recursos adicionales

- Fabric: https://fabricmc.net/
- NeoForge: https://neoforged.net/
- CurseForge: https://www.curseforge.com/minecraft
- Modrinth: https://modrinth.com/

---

## Soporte

Si tienes problemas:
- Revisa la sección de Issues en este repositorio
- Consulta el README de cada mod para información específica
- Lee la documentación oficial del loader que uses
