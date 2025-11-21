🏆 Simulador de Examen AWS

Una aplicación de escritorio diseñada con CustomTkinter para simular preguntas del examen de certificación de AWS, proporcionando una práctica efectiva y retroalimentación visual inmediata.


⚙️ Instalación y Configuración

Sigue estos pasos detallados para poner en marcha el simulador en tu máquina.

1. Requisitos Previos

Asegúrate de tener instalado:

    Python 3.9 o superior (Necesario para la creación del entorno virtual).

    Git (Para clonar el repositorio).

2. Clonar el Repositorio

Abre tu terminal o línea de comandos y ejecuta:
Bash

git clone https://github.com/AldoNava/SimuladorExamen.git
cd SimuladorExamen

3. Crear y Activar el Entorno Virtual (Venv)

Es crucial usar un Entorno Virtual (.venv) para aislar las librerías del proyecto de tu instalación global de Python, garantizando la compatibilidad.

Creación del Entorno

El comando python3.9 -m venv .venv crea el entorno virtual específicamente con la versión 3.9.
Bash

# Crea un entorno virtual llamado .venv usando Python 3.9
python3.9 -m venv .venv 

Activación del Entorno

El proceso de activación varía según el sistema operativo:
Sistema Operativo	Comando de Activación
Windows (CMD/PowerShell)	.\.venv\Scripts\activate
Linux/macOS	source .venv/bin/activate

Verás que (.venv) aparece en tu terminal, confirmando que el entorno está activo.

4. Instalar Dependencias

Con el entorno virtual activado, instala todas las librerías necesarias. Nota: pywin32 solo se requiere si usas la aplicación en Windows; se instalará automáticamente para sistemas compatibles.
Bash

pip install -r requirements.txt

🚀 Ejecución del Simulador

Una vez instaladas las dependencias, inicia la aplicación ejecutando el script principal:
Bash

python main.py


🏗️ Estructura del Proyecto

    main.py: Script principal que inicializa la interfaz gráfica y maneja la lógica del examen.

    requirements.txt: Lista de dependencias del proyecto (customtkinter, pywin32).

🤝 Contribuciones

¡Tu ayuda es bienvenida!

Si encuentras un error, una pregunta mal formulada, o quieres sugerir una mejora, por favor:

    Abre un Issue describiendo el problema.

    Para código, haz un fork del repositorio y envía un Pull Request.
