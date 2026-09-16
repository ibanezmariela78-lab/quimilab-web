# QuimiLab EDU

**Química y laboratorio, paso a paso.**

QuimiLab EDU es una plataforma educativa interactiva desarrollada para integrar **química, cálculo, laboratorio, seguridad y tecnología** en una misma herramienta digital.

Está orientada especialmente a estudiantes de **4.º, 5.º, 6.º y 7.º año de escuelas secundarias técnicas**, docentes de química y espacios de formación vinculados con prácticas de laboratorio.

## 🌐 Probar la plataforma

### QuimiLab EDU Web
**Acceso público:**  
https://quimilab-eduvercelapp.vercel.app

No requiere instalación, Expo Go ni software adicional. Puede utilizarse directamente desde computadora, tablet o teléfono mediante un navegador web.

## 📱 Versiones del proyecto

### Versión Web
Repositorio:  
https://github.com/ibanezmariela78-lab/quimilab-web

### Versión Mobile
Repositorio:  
https://github.com/ibanezmariela78-lab/quimilab

La versión móvil fue desarrollada con React Native y Expo. El build de producción para Android ya fue generado y se encuentra preparado para una futura publicación en Google Play.

## 💡 ¿Qué permite hacer QuimiLab EDU?

- Resolver cálculos químicos.
- Preparar soluciones y otras experiencias de laboratorio.
- Trabajar con molaridad, molalidad, normalidad, formalidad y porcentajes.
- Resolver diluciones y concentraciones traza.
- Calcular preparaciones a partir de reactivos comerciales.
- Consultar los 118 elementos de la tabla periódica.
- Investigar propiedades de sustancias.
- Consultar instrumental y materiales de laboratorio.
- Incorporar criterios de seguridad química.
- Generar informes finales de laboratorio en PDF.
- Relacionar el cálculo teórico con la práctica experimental.

## 🎯 Necesidad que dio origen al proyecto

QuimiLab EDU surge a partir de una problemática frecuente en la enseñanza de la química: el estudiante puede aprender una fórmula y obtener un resultado numérico sin comprender completamente cómo ese cálculo se relaciona con una situación real de laboratorio.

La plataforma busca reducir esa distancia entre **teoría y práctica**, ayudando a interpretar qué se calcula, qué sustancias intervienen, qué instrumental se necesita, qué precauciones deben considerarse y cómo documentar correctamente una experiencia.

## Objetivo

El proyecto busca acompañar el aprendizaje de química con una herramienta clara, guiada y científicamente consistente. La aplicación no se limita a resolver cálculos: también ayuda a interpretar qué se está preparando, qué materiales conviene utilizar, qué precauciones deben considerarse y cómo documentar la experiencia de laboratorio.

## Funcionalidades principales

### Preparación de laboratorio

Permite trabajar con distintos tipos de preparación y concentración:

- Molaridad
- Molalidad
- Normalidad
- Formalidad
- Porcentaje masa/masa
- Porcentaje masa/volumen
- Porcentaje volumen/volumen
- Fracción molar
- ppm y ppb
- Diluciones
- Preparaciones a partir de reactivos comerciales
- Sistemas sólido + líquido
- Sistemas sólido + sólido
- Sustancias viscosas o semisólidas

La aplicación calcula cantidades, identifica materiales necesarios, muestra resultados teóricos y genera orientaciones compatibles con criterios de laboratorio escolar.

### Calculadora química

Incluye herramientas para:

- Masa molar
- Molaridad
- Molalidad
- Normalidad
- Formalidad
- Porcentajes
- Fracción molar
- Concentraciones traza
- Diluciones
- Reactivos comerciales
- Conversión de concentraciones

### Tabla periódica

Incluye los 118 elementos y permite buscar por:

- Nombre
- Símbolo
- Número atómico

Cada elemento cuenta con una ficha individual con información básica para consulta educativa.

### Sustancias y materiales

La aplicación incorpora una biblioteca de sustancias y una biblioteca de materiales de laboratorio.

En sustancias se puede consultar información como:

- Fórmula
- Propiedades
- Solubilidad
- Comportamiento frente a la temperatura
- Observaciones de seguridad

En materiales se informa:

- Para qué sirve cada instrumento
- Cuándo se utiliza
- Cuándo no conviene utilizarlo
- Nivel de precisión
- Estados físicos asociados
- Ejemplos de uso
- Recomendaciones de seguridad

### Informe final de laboratorio

QuimiLab EDU permite generar un informe final combinando:

- Datos ingresados por el estudiante
- Objetivo
- Fundamentación
- Resultado experimental
- Observaciones
- Conclusión
- Sustancias utilizadas
- Cálculos
- Resultado teórico
- Materiales
- Procedimiento
- Seguridad

El informe puede guardarse como borrador y luego generarse y compartirse en formato PDF.

## Criterios científicos incorporados

El proyecto fue diseñado respetando criterios importantes de química experimental, entre ellos:

- El volumen final de una solución no se interpreta automáticamente como volumen de agua agregada.
- En porcentaje m/m se trabaja con la masa total de la mezcla.
- En porcentaje v/v no se asume aditividad ideal de volúmenes.
- La normalidad depende de la reacción y del factor de equivalencia.
- Los reactivos comerciales concentrados requieren considerar concentración y densidad.
- Las sustancias viscosas o semisólidas pueden requerir estrategias basadas en masa o densidad.
- Un sólido en agua no se clasifica automáticamente como solución.
- Sistemas inmiscibles no se presentan automáticamente como emulsiones.
- Cuando la información química no es suficiente, la aplicación evita inventar propiedades o comportamientos.

## Seguridad

QuimiLab EDU tiene un enfoque educativo.

Las sustancias o procedimientos que pueden implicar riesgo se presentan de manera teórica y con advertencias. La aplicación no reemplaza la supervisión docente, las normas institucionales ni los protocolos de seguridad de laboratorio.

## Tecnologías y herramientas utilizadas

QuimiLab EDU fue desarrollado combinando herramientas de programación, desarrollo móvil, desarrollo web, control de versiones, validación, compilación y despliegue.

### Lenguajes y tecnologías base

- TypeScript
- JavaScript
- React 19
- React DOM
- React Native
- React Native Web

### Ecosistema Expo

- Expo SDK 57
- Expo Router
- Expo Constants
- Expo File System
- Expo Font
- Expo Haptics
- Expo Image
- Expo Linking
- Expo Print
- Expo Sharing
- Expo Splash Screen
- Expo Status Bar
- Expo Symbols
- Expo System UI
- Expo Web Browser
- Expo Vector Icons
- Expo/ngrok

### Navegación, interfaz y almacenamiento

- React Navigation Native
- React Navigation Bottom Tabs
- React Navigation Elements
- React Native Gesture Handler
- React Native Reanimated
- React Native Safe Area Context
- React Native Screens
- React Native Worklets
- AsyncStorage

### Desarrollo y ejecución

- Node.js
- npm
- Visual Studio Code
- PowerShell
- Windows
- Metro Bundler
- Expo Go durante desarrollo y pruebas
- Navegadores web para pruebas
- `serve` para pruebas locales de la exportación web

### Desarrollo web

- Expo Web
- React Native Web
- Exportación estática mediante `expo export --platform web`
- Directorio de producción `dist`
- Vercel
- Integración GitHub → Vercel
- Despliegue continuo desde el repositorio web

### Desarrollo y compilación móvil

- EAS CLI
- EAS Build
- Android Keystore administrado mediante EAS
- Build de producción Android en formato AAB
- Configuración de producción para Android
- Configuración de proyecto para iOS

### Control de versiones

- Git
- GitHub
- Repositorio independiente para versión móvil
- Repositorio independiente para versión web

### Calidad, revisión y validación

- TypeScript Compiler (`tsc`)
- ESLint
- eslint-config-expo
- Expo Doctor
- `git diff --check`
- Validaciones de compilación web
- Pruebas funcionales en Android
- Pruebas funcionales en navegador
- Revisión visual responsiva

### Generación y gestión de documentos

- expo-print
- expo-sharing
- expo-file-system
- Generación de informes finales en PDF
- Persistencia de borradores con AsyncStorage

### Diseño e identidad visual

- Procesamiento de imágenes mediante PowerShell y System.Drawing
- Recursos gráficos PNG
- Configuración de iconos adaptativos Android
- Splash screen
- Favicon web
- Diseño responsivo para móvil y escritorio

### Inteligencia artificial aplicada al desarrollo

- ChatGPT / OpenAI como asistencia durante planificación, programación, depuración, documentación, revisión científica, diseño de interfaz y desarrollo del proyecto

### Infraestructura y publicación

- GitHub para código fuente y documentación
- Vercel para hosting de la versión web
- Expo Application Services (EAS) para builds móviles
- Google Play Console preparada para futura publicación Android
- LinkedIn para presentación profesional del proyecto

### Plataformas y dispositivos utilizados para pruebas

- Android
- iPhone durante desarrollo con Expo Go
- Windows
- Chrome
- Edge
- Navegadores móviles
- Navegadores de escritorio
## Estructura general

```text
app/
components/
chemistry/
data/
hooks/
```

La aplicación utiliza rutas independientes para cada módulo y componentes reutilizables para los cálculos y las preparaciones.

## Instalación

Requisitos:

- Node.js
- npm
- Expo

Clonar el repositorio:

```bash
git clone https://github.com/ibanezmariela78-lab/quimilab.git
cd quimilab
npm install
```

Iniciar el proyecto:

```bash
npx expo start
```

Si la red local presenta problemas de conexión:

```bash
npx expo start --tunnel
```

## Validación del proyecto

El proyecto se valida con:

```bash
npx tsc --noEmit
npx eslint app chemistry components data hooks
npx expo-doctor
git diff --check
```

Estado de la última revisión técnica:

- TypeScript sin errores
- ESLint sin errores
- Expo Doctor: 21/21 checks passed
- Árbol de trabajo Git limpio

## Estado del proyecto

QuimiLab EDU se encuentra en una etapa funcional avanzada, con los módulos principales integrados y revisados.

El proyecto continúa abierto a mejoras de experiencia de usuario, ampliación de sustancias, nuevos contenidos educativos y distribución como aplicación instalable.

## Repositorio

GitHub: https://github.com/ibanezmariela78-lab/quimilab

---

Autora: Mariela Ibañez  
Teléfono: +54 11 4058-2174  
GitHub: https://github.com/ibanezmariela78-lab  
LinkedIn: https://ar.linkedin.com/in/mariela-ibanez-quimioinformatica
