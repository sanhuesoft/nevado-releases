# Nevado

**Nevado** es una aplicación de gestión de conocimiento personal y Zettelkasten diseñada específicamente para macOS, donde la velocidad y la profundidad semántica convergen. Construida con un enfoque en el rendimiento nativo y la usabilidad, Nevado permite transformar una carpeta local de archivos Markdown en un cerebro digital interconectado.

## Características Principales

### 🧠 Gestión de Conocimiento (Zettelkasten)
- **Vault System:** Gestión completa de bóvedas locales. La aplicación escanea y sincroniza archivos Markdown en tiempo real, manteniendo la integridad de tus datos sin depender de la nube.
- **Identificadores Zettel:** Implementación nativa de IDs basados en tiempo y metadatos para una organización robusta y enlaces permanentes.
- **Backlinks y Relaciones:** Rastreo automático de conexiones entre notas, permitiendo una navegación fluida a través de hilos de pensamiento.

### 🕸️ Visualización de Grafo Dinámico
- **Motor de Simulación Personalizado:** Nevado utiliza un motor de simulación de fuerzas optimizado mediante **QuadTree** para representar visualmente tu red de notas.
- **Interactividad en Tiempo Real:** Explora visualmente la densidad de tus conocimientos, identifica clústeres de información y navega hacia las notas directamente desde el grafo.
- **Rendimiento Escalable:** Diseñado para manejar cientos de nodos y conexiones sin degradar la fluidez de la interfaz.

### 🔍 Inteligencia Artificial y Búsqueda Semántica
- **Semantic Search Service:** Ve más allá de las palabras clave. Nevado indexa el contenido para permitir búsquedas basadas en el significado y el contexto.
- **Auto-completado Inteligente:** Sugerencias contextuales mientras escribes, facilitando la creación de enlaces y la recuperación de información existente.
- **Integración de IA:** Soporte para servicios de IA que ayudan a resumir, expandir o conectar ideas dentro de tu flujo de trabajo.

### 📚 Bibliografía y Referencias
- **Gestión de Referencias:** Módulo dedicado para crear y gestionar entradas bibliográficas.
- **Selector de Bibliografía:** Lanzador rápido para insertar citas y referencias técnicas sin interrumpir la escritura.

### ⌨️ Interfaz y Usabilidad (Launcher)
- **Paleta de Comandos (Launcher):** Un centro de control rápido inspirado en los mejores flujos de trabajo de productividad. Busca notas, ejecuta comandos y cambia de contexto mediante atajos de teclado.
- **Diseño Nativo:** Integración total con la estética y las directrices de diseño de macOS, ofreciendo una experiencia refinada y predecible.

## Arquitectura Técnica

Nevado ha sido desarrollada bajo una arquitectura híbrida que prioriza la velocidad de procesamiento y la fidelidad visual:

- **Swift 5 & SwiftUI:** El núcleo de la aplicación y la interfaz de usuario están escritos íntegramente en Swift 5. Esto garantiza un consumo de recursos mínimo, una gestión de memoria eficiente y una respuesta instantánea a las interacciones del usuario.
- **Operación Nativa:** Todo el procesamiento de archivos, indexación de búsqueda, motor de simulación de grafos y gestión de la interfaz ocurre de forma nativa en el sistema.
- **Renderizado de Notas (WebView):** Para garantizar una visualización rica y precisa de Markdown (incluyendo soporte para tablas, fórmulas y estilos complejos), Nevado utiliza componentes de WebView específicamente para la capa de presentación de las notas parseadas, manteniendo el resto de la experiencia 100% nativa.

## Requisitos del Sistema

- **Plataforma:** macOS (Optimizado para las versiones más recientes).
- **Lenguaje:** Swift 5.
- **Almacenamiento:** Local (Privacidad total por diseño).

## Instalación

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/nevado.git](https://github.com/tu-usuario/nevado.git)
