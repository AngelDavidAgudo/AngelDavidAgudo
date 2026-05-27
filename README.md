En cuanto pueda subire un extracto de los proyectos en los que he trabajado y trabajo actualmente.

Indice.

Proyecto 1: ShortMaker, el creador de videos cortos para redes sociales.
Proyecto 2: MultiCam, el visor y grabador de camaras de seguridad para el hogar y la pequeña empresa.
Proyecto 3:
Proyecto 4:
Proyecto 5:

PROYECTO 1 # 🎬 ShortsMaker - Creador de Shorts para Editor Profesional de Video

ShortsMaker es una herramienta de escritorio desarrollada desde cero para optimizar el flujo de trabajo en la creación de YouTube Shorts. Permite la edición de precisión, previsualización aislada y renderizado asíncrono en una interfaz gráfica fluida y profesional.

---

UI:
<img width="1240" height="1280" alt="ShortMakerV1" src="https://github.com/user-attachments/assets/c0145fe7-eec2-469a-b402-c33629cf4e2b" />

Funcionamiento: 
https://github.com/user-attachments/assets/4ad72986-bd62-4f3d-9d7b-52af52305709

Resultado:
https://github.com/user-attachments/assets/61c44cc2-d8ff-49e3-947e-12ff4cf3276b

---

Características Principales

* Doble Visor Sincronizado: Reproductor principal para el metraje original y visor secundario independiente para la previsualización en bucle del Short seleccionado.
* Corte de Alta Precisión: Sistema de marcadores de Entrada/Salida (In/Out) con botones de ajuste de milisegundos (`+1s`, `-1s`, `+10s`, `-10s`) integrados en una cuadrícula (Grid) para un ajuste milimétrico.
* Motor Asíncrono (Multithreading): El procesamiento de video se ejecuta en un hilo secundario (Worker), manteniendo la interfaz 100% receptiva. Incluye cancelación de emergencia segura.
* Feedback en Tiempo Real: Extracción de logs de renderizado para alimentar una barra de progreso nativa que muestra el porcentaje exacto de exportación.
* Gestión Inteligente de Archivos: Creación automática de carpetas correlativas para exportaciones y recolección de basura (auto-limpieza) de archivos temporales de audio y video.

---

Stack Tecnológico

* Lenguaje: Python 3
* Interfaz Gráfica (GUI): PyQt6 (Gestión avanzada de QLayouts, QThreads y Custom Widgets)
* Procesamiento Multimedia: MoviePy 2.0+ (Manipulación de subclips, recortes 9:16, redimensionado a 1080x1920 y codificación H.264/AAC)
* Arquitectura: Diseño modular separando la lógica de la interfaz (UI) del motor de procesamiento (Core).
