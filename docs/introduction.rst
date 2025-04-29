====================================
Introduction
====================================

Esta documentación describe el modelo OSeMOSYS-RD, desarrollado en colaboración con el Programa de las
Naciones Unidas para el Desarrollo (PNUD) y la Organización de las Naciones Unidas para la Alimentación y
la Agricultura (FAO) para evaluar las emisiones de gases de efecto invernadero (GEI) en República Dominicana hacia el año 2050.

El modelo permite:

    - Evaluar las trayectorias de emisiones bajo diferentes escenarios.
    - Comparar el escenario tendencial con una estrategia baja en carbono y resiliente.
    - Desagregar resultados por sector, tipo de gas y año.
    - El modelado se basa en OSeMOSYS, un marco de código abierto ampliamente utilizado para evaluar políticas de mitigación y planificación energética, y emplea la metodología de Toma de Decisión Robusta (RDM) para incorporar la incertidumbre en la construcción de escenarios.

-------------------------------------
Estructura de Archivos
-------------------------------------

Para facilitar la navegación, la documentación sigue la siguiente estructura de archivos:

.. code-block:: none

   docs/
   │── index.rst                              # Página principal
   │── introduccion.rst                       # Introducción
   │   └── 1_estructura_archivos.rst          # Estructura de Archivos
   │── metodologia.rst                        # Metodología general
   │── resultados_nacionales.rst              # Resultados Nacionales
   │── energia/                               # Sector Energía y Transporte
   │   ├── 0_estructura.rst                   # Estructura del modelo
   │   ├── 1_entradas.rst                     # Datos de entrada
   │   ├── 2_escenarios.rst                   # Escenarios
   │   ├── 3_resultados.rst                   # Resultados
   │   └── 4_referencias.rst                  # Referencias
   │── agricultura/                           # Agricultura, Silvicultura y Cambio de Uso de la Tierra (AFOLU)
   │── procesos/                              # Procesos Industriales y Uso de Productos (PIUP)
   │── residuos/                              # Sector Residuos
   │── uso_modelo/                            # Uso del Modelo
   │── github_navigation.rst                  # Navegación en GitHub
   │── license.rst                            # Información sobre la licencia
   │── authors.rst                            # Créditos y autores
   │── source/                                # Carpeta de recursos
   │   └── _static/
   │       └── _images/                       # Imágenes utilizadas en la documentación



