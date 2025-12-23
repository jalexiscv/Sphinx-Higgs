******************
Sphinx Higgs Theme
******************

.. image:: https://img.shields.io/badge/version-1.0.0-blue.svg
   :alt: Version
.. image:: https://img.shields.io/badge/license-MIT-green.svg
   :target: https://github.com/jalexiscv/Sphinx-Higgs/blob/main/LICENSE
   :alt: License

Un tema profesional y personalizable para Sphinx, basado en el popular tema Read the Docs.

Características
===============

Este tema Sphinx fue diseñado para proporcionar una excelente experiencia de lectura para
los usuarios de documentación tanto en dispositivos de escritorio como móviles.

* Diseño responsive y moderno
* Navegación intuitiva
* Soporte para múltiples idiomas
* Totalmente personalizable
* Compatible con las últimas versiones de Sphinx

Instalación
===========

Este tema se puede instalar usando ``pip``:

.. code:: console

   $ pip install sphinx-higgs

Para usar el tema en tu proyecto Sphinx, necesitas editar el archivo ``conf.py``
y configurar la opción ``html_theme``:

.. code:: python

    html_theme = "sphinx_higgs"

Requisitos
==========

* Python >= 3.8
* Sphinx >= 6.0
* docutils > 0.18, < 0.22
* sphinxcontrib-jquery >= 4

Configuración
=============

Este tema es altamente personalizable tanto a nivel de página como a nivel global.
Para ver todas las opciones de configuración posibles, consulta la documentación
de configuración del tema original en
`sphinx-rtd-theme.readthedocs.io <https://sphinx-rtd-theme.readthedocs.io/en/stable/configuring.html>`_.

Origen y Licencia
=================

Este tema es un fork del excelente `sphinx_rtd_theme <https://github.com/readthedocs/sphinx_rtd_theme>`_
desarrollado por Read the Docs, Inc. y contribuidores.

**Mantenedor:** Jose Alexis Correa Valencia

**Licencia:** MIT

Desarrollo
==========

Para contribuir al desarrollo de este tema o reportar problemas,
visita el repositorio en GitHub:

https://github.com/jalexiscv/Sphinx-Higgs

Créditos
========

Este proyecto está basado en el trabajo original de:

* Dave Snider
* Read the Docs, Inc. y contribuidores

Agradecemos su excelente trabajo que hizo posible este proyecto.
