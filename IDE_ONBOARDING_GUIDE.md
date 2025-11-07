# Guía de Configuración de Entornos de Desarrollo

> 📋 **Guía Técnica**: Esta documentación establece los procedimientos para configurar un entorno de desarrollo en C# y otros lenguajes. Incluye las configuraciones necesarias para mantener consistencia en el desarrollo de software.

> **Nota importante**: Este documento se enfoca en aspectos técnicos y procedimientos. Para análisis comparativos, reflexiones personales y conclusiones, utiliza el archivo `CONCLUSIONES_EVALUACION.md`.

**Autores**: [] y []
**Fecha V0**: []
**Fecha V1**: [Fecha de entrega final]

---

## Visual Studio Code - Entorno Principal

### Instalación y Verificación

**Método de instalación:** [Descarga web: https://code.visualstudio.com/]

> **💡 Sobre las imágenes**: Incluye capturas de pantalla para mostrar los diferentes pasos o resultados. Ejemplo: ![Descripción clara del contenido](screenshots/placeholder.png)`

**Proceso de instalación:**
- **Descarga:** [Para instalar vs Code nos dirigiremos al siguiente link https://code.visualstudio.com/ y le daremos al botón Download for Windows.] [la interfaz de la pagina](screenshots/foto1.png)
- **Opciones del instalador:** [ Podemos elejir entre cargas de trabajo, componentes individuales, paquetes de idiomas, ubicacion del insalador, importar configuracion / migrar configuracion, opciones de descarga y modificar, reparar / instalacion ] [el stable]
- **Verificación:** [Cómo verificar que funcion muy facil probando cun cualquier lenguaje y haciendo un hello word]

*Es posible documentar múltiples métodos.*

### Uso Básico de VS Code

**Navegación y funcionalidades básicas:**
- Navegación por la interfaz
- Edición de código
- Uso de la paleta de comandos
- Gestión de archivos y carpetas

### Personalización del Entorno

**Configuraciones aplicadas:** [Se aplicaron las siguientes configuraciones: Palenight Theme, Prettier, Live server, indent-rainbow]

*Ejemplos de configuraciones útiles (elegir las que se consideren relevantes):*

**Temas e iconos:**
Ejemplos:
- Material Theme, One Dark Pro
- File Icon Theme para mejor identificación de archivos

**Configuración de fuentes:**
Ejemplos:
- Fira Code, JetBrains Mono (con ligaduras)

**Atajos de teclado útiles:**
Ejemplos:
- F5 para ejecutar el codigo
- Ctrl+/ para comentar/descomentar
- Ctrl+Shift+P para paleta de comandos
- Ctrl+` para terminal integrada
- Alt+↑/↓ para mover líneas

**Configuración del editor:**
Ejemplos:
- Formateo automático al guardar
- Detección automática de indentación
- Word wrap para líneas largas

**Terminal integrada:**
Ejemplos:
- PowerShell como terminal predeterminado
- Configuración de perfil personalizado

> **Personaliza según tus necesidades**: Estas son sugerencias basadas en prácticas comunes. Experimenta y documenta las configuraciones que encuentres más útiles para tu flujo de trabajo.> 💼 **Manual de Incorporación**: Esta guía establece los estándares del equipo para configurar entornos de desarrollo en C#. Cualquier nuevo desarrollador debe poder seguir estas instrucciones para configurar su entorno de trabajo de manera consistente con el resto del equipo.

### SDK .NET

**Proceso de instalación:**
1. **Descarga e instalación:** [Para instalar el SDK de .NET, debe dirigirse al sitio oficial de descargas disponible en https://dotnet.microsoft.com/en-us/download
, seleccionar la versión requerida y descargar el instalador correspondiente al sistema operativo utilizado. Una vez descargado, ejecute el instalador y siga las instrucciones proporcionadas.] [captura de la interfaz de la web](placeholder4.png)
2. **Verificación:** [Para comprobar que la instalación se ha realizado correctamente, abra una terminal o consola y ejecute el siguiente comando: dotnet --version. Si la instalación fue exitosa, se mostrará en pantalla el número de versión instalada, lo que confirmará que el SDK está correctamente configurado.]

### Configuración para C#

**Extensiones esenciales:**
- **Soporte oficial para C#**: Se recomienda instalar la extensión oficial de C# disponible en el marketplace de Visual Studio Code, la cual proporciona soporte para funcionalidades clave como IntelliSense, depuración y compilación del código.


**Configuraciones específicas para C#:** 
Es importante establecer configuraciones que mejoren la experiencia de desarrollo, tales como el formateo automático del código al guardar, la habilitación de sugerencias inteligentes (IntelliSense) y ajustes personalizados del compilador. Estas configuraciones pueden aplicarse directamente desde el archivo settings.json del editor.

**Debugging básico:**
Para depurar aplicaciones en C#, se debe configurar adecuadamente el entorno permitiendo el uso de puntos de interrupción (breakpoints), la ejecución paso a paso y la inspección de variables durante la ejecución. Estas funciones básicas permiten identificar y resolver errores de forma eficiente.

**Enfoque práctico:** 
La documentación debe centrarse en las funcionalidades esenciales que se utilizan en el trabajo cotidiano, evitando configuraciones innecesarias o avanzadas que no aporten valor directo al flujo de desarrollo.

### Flujo de Trabajo con C#

**Creación de proyectos:**
[Documentar el proceso para crear proyectos C#]

**Estructura de proyecto:**
```csharp
// Incluir aquí un ejemplo del código desarrollado
// Comentarios sobre las decisiones tomadas
```

**Compilación y ejecución:**
[Proceso para compilar y ejecutar proyectos]

**Debugging:**
[Configuración y uso de debugging]

---

## Visual Studio - IDE Alternativo

### Instalación

**Proceso de instalación:**
- **Descarga:** [Versión recomendada - Community/Professional]
- **Componentes necesarios:** [Componentes específicos para C#]
- **Verificación:** [Cómo confirmar instalación correcta]

### Desarrollo con C#

**Creación de proyecto:**
[Describir el proceso para crear un proyecto C# en Visual Studio]

**Flujo de trabajo básico:**
- Compilación y ejecución
- Uso de Solution Explorer
- Debugging básico

---

## Configuración de Lenguaje Adicional

**Lenguaje seleccionado:** [Java/Python/Otro] - **Justificación:** [Por qué se eligió este lenguaje]

### Instalación del Entorno

**Runtime/SDK:**
- **Descarga e instalación:** [Proceso paso a paso]
- **Verificación:** [Cómo confirmar que funciona]

### Configuración en VS Code

**Extensiones por lenguaje:**

*Para Java:*
- **Paquete completo de Java**: Incluye compilación, debugging y gestión de proyectos

*Para Python:*
- **Soporte oficial de Python**: Extensión completa con intérprete y debugging

*Para otros lenguajes:*
- Busca la extensión oficial del lenguaje que proporcione soporte completo

**Configuraciones específicas aplicadas:**
[Documentar los ajustes que se realizaron, como configuración del intérprete, formateo automático, linting, etc.]

### Proyecto de Ejemplo

**Código desarrollado:**
```[lenguaje]
// Código de ejemplo aquí
// Comentarios explicativos
```

**Proceso de ejecución:**
[Describir cómo ejecutar el código]

---

## Configuraciones Recomendadas

**Configuraciones generales:**
[Documentar configuraciones que se consideran útiles para cualquier desarrollador]

**Herramientas adicionales:**
[Extensions, herramientas CLI, o utilidades que se consideran beneficiosas]

**Solución de problemas comunes:**
[Problemas frecuentes durante la configuración y sus soluciones]

**Recursos útiles:**
- Enlace [Enlace]: [Descripción]
- Documentación [Documentación]: [Descripción]

---
