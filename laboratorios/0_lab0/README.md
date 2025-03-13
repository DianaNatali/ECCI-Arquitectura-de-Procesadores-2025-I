# Lab 00: Instalación de herramientas 

En este laboratorio nos enfocaremos en la instalación y configuración de las herramientas esenciales para el desarrollo de este curso.


## 1. *FPGA Design Software* - Quartus (Para síntesis en FPGA Cyclone IV)

Quartus es un software de diseño digital e implementación FPGA desarrollado por Intel (anteriormente Altera). Es ampliamente utilizado para la síntesis, implementación y verificación de diseños digitales en FPGAs de la familia Cyclone.

* [Guía de instalación](/laboratorios/0_lab0/Quartus_installation_guide.md)

* [Tutorial de implementación en la FPGA Cyclone IV](/laboratorios/0_lab0/proyectoQuartus.md)

## 2. Herramientas de simulación *Open Source*:

1. ### Icarus Verilog

  Icarus Verilog es una herramienta de simulación de código abierto para HDL (*Hardware Description Language*). Es ideal para simular y verificar diseños digitales antes de su implementación en hardware.

  * [Guía de instalación](/laboratorios/0_lab0/iverilog.md)

2. ### Digital - Simulador de circuitos

   * [Digital - Simulador de circuitos](/laboratorios/0_lab0/digital.md)


## 3. Visual Studio Code (Editor de código)

Visual Studio Code (VS Code) es un editor de código ligero pero potente, desarrollado por Microsoft. Es altamente personalizable y cuenta con una amplia gama de extensiones que lo hacen ideal para el desarrollo de software y hardware.

* Descarga de Visual Studio Code: https://code.visualstudio.com/

* Tutorial de instalación y configuración:

    1. Descarga el instalador desde el enlace anterior.

    2. Sigue las instrucciones del instalador para completar la instalación.

    3. Una vez instalado, abre VS Code y explora las extensiones disponibles en el marketplace (por ejemplo, extensiones para Verilog, Git, etc.).


## 4. Git y GitHub

Git es un sistema de control de versiones ampliamente utilizado para gestionar proyectos de software y hardware. GitHub es una plataforma basada en Git que permite alojar repositorios y colaborar en proyectos.

* Descarga de Git: https://git-scm.com/

* Tutorial de instalación y uso básico de Git:

    1. Descarga Git desde el enlace anterior.

    2. Sigue las instrucciones del instalador.

    3. Configura Git con tu nombre y correo electrónico:

       En una terminar del sistema operativo ejecutar:

       ```
       git config --global user.name "Tu Nombre"
       git config --global user.email tu@email.com
       ```

    4. Aprende los comandos básicos de Git:

        * ```git init```: Inicializa un repositorio.

        * ```git clone <url>```: Clona un repositorio remoto.

        * ```git add <archivo>```: Añade archivos al área de preparación.

        * ```git commit -m "mensaje"```: Guarda los cambios en el repositorio.

        * ```git push```: Sube los cambios al repositorio remoto.

        * ```git pull```: Actualiza el repositorio local con los cambios remotos.

* Tutorial de GitHub:

    1. Crea una cuenta en GitHub.

    2. Aprende a crear un repositorio, hacer commits, crear ramas y colaborar en proyectos.

    3. Explora la documentación oficial de GitHub: https://docs.github.com/.