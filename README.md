# Minecraft Mods & Plugins Repository

Bienvenido al repositorio público de mods y plugins para Minecraft. Este proyecto está diseñado para facilitar a usuarios novatos el acceso a modificaciones básicas para mejorar su experiencia de juego.

## Tabla de contenidos

- [¿Qué es este repositorio?](#qué-es-este-repositorio)
- [¿Qué loader necesito?](#qué-loader-necesito)
- [Estructura del repositorio](#estructura-del-repositorio)
- [¿Cómo sé qué versión tengo?](#cómo-sé-qué-versión-tengo)
- [Cómo descargar e instalar](#cómo-descargar-e-instalar)
- [Contribuir al repositorio](#contribuir-al-repositorio)
- [Licencia](#licencia)

---

## ¿Qué es este repositorio?

Este es un repositorio **colaborativo y público** donde cualquiera puede:
- **Descargar** mods y plugins organizados por versión y tipo
- **Subir** sus propios mods para compartir con la comunidad
- **Encontrar** modificaciones compatibles con su versión específica de Minecraft

Nuestro objetivo es centralizar recursos y simplificar el proceso de modding para usuarios de todos los niveles.

---

## ¿Qué loader necesito?

Antes de descargar mods, hay que entender qué "loader" (cargador de mods) usar. Aquí te explicamos las diferencias:

### Vanilla (sin mods)
- **¿Qué es?** Minecraft puro, sin modificaciones
- **¿Para quién?** Jugadores que no quieren instalar loaders pero buscan datapacks o recursos básicos
- **Ventajas:** No requiere instalación adicional
- **Desventajas:** Muy limitado en modificaciones

### Fabric
- **¿Qué es?** Un loader ligero y moderno para mods
- **¿Para quién?** Usuarios que buscan mods de optimización, utilidades y modificaciones técnicas
- **Ventajas:**
  - Muy rápido y eficiente
  - Se actualiza rápidamente a nuevas versiones de Minecraft
- **Desventajas:** Menos mods de contenido masivo comparado con Forge o NeoForge
- **Instalación:** Descarga el instalador desde [fabricmc.net](https://fabricmc.net)

### NeoForge
- **¿Qué es?** La evolución de Forge, el loader tradicional
- **¿Para quién?** Usuarios que buscan mods de contenido, aventura y modificaciones grandes
- **Ventajas:**
  - Mayor cantidad de mods de contenido disponibles
  - Compatible con muchos modpacks populares
  - Excelente para mods complejos y grandes modificaciones
- **Desventajas:** Más pesado que Fabric
- **Instalación:** Descarga el instalador desde [neoforged.net](https://neoforged.net)

**Nota importante:** Fabric y NeoForge NO son compatibles entre sí. Los mods de Fabric no funcionan en NeoForge y viceversa.

---

## Estructura del repositorio

```
Java/
├── Vanilla/
│   ├── 1.0–1.5/
│   ├── 1.6–1.8/
│   ├── 1.9–1.12/
│   ├── 1.13–1.16/
│   ├── 1.17/
│   ├── 1.18/
│   ├── 1.19/
│   ├── 1.20/
│   │   ├── 1.20.0/
│   │   ├── 1.20.1/
│   │   ├── 1.20.2/
│   │   ├── 1.20.3/
│   │   ├── 1.20.4/
│   │   ├── 1.20.5/
│   │   └── 1.20.6/
│   └── 1.21/
│       ├── snapshots/
│       └── releases/
│
├── Fabric/
│   ├── 1.14–1.16/
│   ├── 1.17/
│   ├── 1.18/
│   ├── 1.19/
│   ├── 1.20/
│   └── 1.21/
│
├── NeoForge/
│   ├── 1.20/
│   └── 1.21/
│
└── Shaders/
    ├── 1.7–1.12/
    ├── 1.13–1.16/
    ├── 1.17–1.20/
    └── 1.21/
```

---

## ¿Cómo sé qué versión tengo?

### Desde el menú principal de Minecraft:
1. Abre Minecraft Launcher
2. En la barra superior, en tu mundo seleccionado verás: **Minecraft 1.20.4** (por ejemplo)

### ¿Cómo sé si tengo Fabric o NeoForge instalado?
Al iniciar Minecraft, en el menú principal verás:
- **Fabric Loader** o botón "Mods" (Fabric)
- **NeoForge** o lista de mods cargados (NeoForge)
- Si no ves nada de esto, tienes Minecraft Vanilla

---

## Cómo descargar e instalar

### Paso 1: Navega a tu carpeta
1. Identifica tu versión exacta (ejemplo: 1.20.4)
2. Identifica tu loader (Fabric, NeoForge, o Vanilla)
3. Ve a: `Java/[TuLoader]/[TuVersión]/`

### Paso 2: Descarga los mods
1. Haz clic en el archivo .jar que quieras descargar
2. Click en el botón "Download" o "Descargar"
3. Guarda el archivo en tu ordenador

### Paso 3: Instala los mods

**Localiza tu carpeta .minecraft:**
- **Windows:** Presiona `Windows + R`, escribe `%appdata%/.minecraft` y pulsa Enter
- **Mac:** `~/Library/Application Support/minecraft`
- **Linux:** `~/.minecraft`

**Copia los archivos:**
1. Abre la carpeta `mods` (créala si no existe)
2. Pega los archivos .jar descargados aquí

**Inicia Minecraft:**
1. Asegúrate de seleccionar el perfil con Fabric o NeoForge instalado
2. Los mods se cargarán automáticamente

### Importante:
- NO mezcles mods de Fabric con NeoForge
- Asegúrate de que la versión del mod coincide exactamente con tu versión de Minecraft
- Algunos mods requieren otros mods como dependencias (esto se indica en su README)

---

## Contribuir al repositorio

¡Las contribuciones son bienvenidas!

### Reglas para colaboradores:

**Organización:**
- Sube los mods a la carpeta correcta según loader y versión exacta
- Nombra los archivos claramente: `nombre-mod-version.jar`

**Archivos permitidos:**
- Solo archivos .jar de mods/plugins
- Archivos README.md con descripción del mod
- Archivos LICENSE si el mod tiene licencia específica

**Archivos NO permitidos:**
- No subas archivos de build, dependencias o temporales
- No subas código fuente (a menos que sea tu propio mod)
- No subas archivos ejecutables sospechosos

**Información requerida:**

Crea o actualiza el README de la carpeta con:
- Nombre del mod
- Versión del mod
- Breve descripción de qué hace
- Autor original
- Link a la fuente oficial (CurseForge, Fabric, etc.)

**Respeto a licencias:**
- Solo sube mods que permitan redistribución
- Incluye el archivo LICENSE si el mod lo requiere
- Da crédito al autor original

### Cómo contribuir:
1. Haz fork del repositorio
2. Crea una nueva rama para tu contribución
3. Añade tus mods en la carpeta apropiada
4. Actualiza el README correspondiente
5. Crea un Pull Request con una descripción clara

**Revisión:** Todos los Pull Requests son revisados antes de ser aceptados para garantizar la calidad y seguridad del repositorio.

---

## Advertencia importante

**¡Revisamos el repositorio diariamente!**

Cualquier archivo incorrecto, malicioso, o que no cumpla las reglas será eliminado inmediatamente. Los colaboradores que suban contenido inapropiado serán bloqueados.

---

## Licencia

Este repositorio está bajo licencia **MIT**. Los mods individuales pueden tener sus propias licencias, que se indican en sus respectivas carpetas.

**Licencia MIT:** Puedes usar, copiar, modificar y distribuir este repositorio libremente, siempre que incluyas el aviso de copyright original.

---
## FAQ - Preguntas frecuentes

### ¿Puedo mezclar mods de Fabric y NeoForge?
No. Fabric y NeoForge son incompatibles entre sí. Debes elegir uno u otro.

### ¿Funcionan estos mods en Bedrock Edition?
No. Este repositorio solo contiene mods para Java Edition. Bedrock Edition tiene limitaciones técnicas para mods.

### ¿Cómo sé si un mod necesita otros mods para funcionar?
Revisa el README en la carpeta del mod. Las dependencias están listadas claramente.

### ¿Los mods afectan el rendimiento?
Algunos mods lo mejoran (Sodium, Lithium) y otros pueden reducirlo. Lee la descripción de cada mod.

---
## Soporte

¿Tienes problemas o preguntas?
- Abre un [Issue](../../issues) en GitHub
- Consulta los README en cada carpeta para información específica

---

## Roadmap

Próximas mejoras planeadas:
- [ ] Guía de instalación detallada con capturas
- [ ] Lista completa de mods recomendados para novatos
- [ ] Sistema de categorías (Optimización, Utilidad, Visual, etc.)
- [ ] Soporte para Bedrock Edition
- [ ] Wiki con tutoriales completos

---

**¡Disfruta y comparte de manera responsable!**
