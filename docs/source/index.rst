Bienvenido a la documentación de mi Proyecto
===================================

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: 🚀 PRUEBAS

   /index
   /docker

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: 💡 Explanation


Descripción breve
--------
Este proyecto	consiste en analizar, diseñar e implementar	una aplicación web que se encargará de la gestión de servicios de una empresa (Gestión Inventario, Gestión de Problemas, Gestión Financiera, Gestión de Proyectos)
Materiales

--------
Se desarrollará teniendo en cuenta las distintas tecnologías aprendidas durante el Ciclo Formativo de Desarrollo de Aplicaciones Web.
Concretamente deberá escribirse usando los siguientes lenguajes:

- PHP como hilo	conductor de toda la aplicación. 
	
- SQL para diseñar las consultas y otros comandos que PHP lanzará a la base de datos.	

- HTML,	Javascript y CSS para construir en tiempo de ejecución la parte visible de la	aplicación que interactuará con el usuario (páginas web dinámicas).


En cuanto a los servidores que necesitarás para que funcione debes usar los siguientes:

-	MySQL

Como sistema gestor de bases de datos donde almacenar los objetos de la base de datos que necesitemos

-	 Apache 

Como servidor web donde alojar las páginas escritas en PHP.	

Las librerías de PHP para que trabaje con MySQL y con Apache.	




Desarrollo
--------
El elemento central de esta aplicación web es la gestión de servicios.


El objetivo de este proyecto es que el alumno sea capaz de hacer	una aplicación web que se encargue, al menos, de:		
- Crear, eliminar y modificar usuarios los cuales tendrán distintos roles dentro de la aplicación.

- Crear, eliminar y modificar productos en el inventario pudiendo asignar estos a los usuarios. Estos productos también tendrán un costo que afectarán a la parte financiera…

- Crear, eliminar, y modificar tickets, los cuales se crearán por los usuarios con roles de usuario y se revisarán por los usuarios con rol de técnico

- Crear, eliminar y modificar proyectos, estos se crearán por los usuarios con roles como manager y se asignarán a los técnicos.



Plazo de entrega
--------
Este Proyecto Fin de Ciclo deberá estar acabado y listo	paraser	defendido al final del período de FCT. Es por tanto, que durante el desarrollo de las prácticas en empresa, el alumno deberá desarrollar en paralelo este trabajo para presentarlo con éxito al finalizar las mismas.






.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: 🪄 How-to guides

   Project setup and configuration </guides/setup/index>
   Build process </guides/build/index>
   Upgrading and maintaining projects </guides/maintenance/index>
   Content, themes and SEO </guides/content/index>
   Security and access </guides/access/index>
   Account management </guides/management/index>
   Best practice </guides/best-practice/index>
   Troubleshooting problems </guides/troubleshooting/index>

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: 📚 Reference

   /reference/features
   /config-file/v2

.. meta::
   :description lang=en: Automate building, versioning, and hosting of your technical documentation continuously on Read the Docs.

.. Adds a hidden link for the purpose of validating Read the Docs' Mastodon profile
.. raw:: html

   <a style="display: none;" rel="me" href="https://fosstodon.org/@readthedocs">Mastodon</a>

|:arrows_counterclockwise:| Up to date documentation
    Whenever you push code to Git,
    Read the Docs will automatically build your docs
    so your code and documentation are always up-to-date.
    Get started with our :doc:`tutorial </tutorial/index>`.

|:card_index_dividers:| Documentation for every version
    Read the Docs can host multiple versions of your docs.
    Keep your 1.0 and 2.0 documentation online,
    pulled directly from Git.
    Start hosting all your :doc:`versions </versions>`.

|:heartbeat:| Open source and user focused
    Our company is bootstrapped and 100% user-focused,
    so our product gets better for our users instead of our investors.
    |org_brand| hosts documentation for over 100,000 large
    and small open source projects.
    |com_brand| supports hundreds of organizations with product and internal documentation.
    Learn more about :doc:`our two platforms </choosing-a-site>`.

First time here?
----------------

We have a few places for you to get started:

.. descriptions here are active

🚀 :doc:`/tutorial/index`
  Take the first practical steps with Read the Docs.

🚀 :doc:`/examples`
  Start your journey with an example project to hit the ground running.

🚀 :doc:`All tutorials </tutorials/index>`
  Using documentation tools like Sphinx or MkDocs for the first time or importing an existing project?
  We have the tutorials to get you started!

Explanation
-----------

Get a high-level overview of our platform:

.. Descriptions here are focused on learning

.. TODO: This next item needs its article to be finished in a separate PR
.. https://github.com/readthedocs/readthedocs.org/pull/10071

💡 :doc:`Continuous Documentation </integrations>`
  Discover the advantages of having your documentation continuously deployed.

💡 :doc:`/choosing-a-site`
  Learn about the differences between |org_brand| and |com_brand|.

💡 :doc:`/explanation/advanced`
  Get familiar with some of the more advanced topics of building and deploying documentation with Read the Docs.

💡 :doc:`All explanation articles </explanation/index>`
  Browse all our explanation articles.


Reference
---------

Need to know how something works?
Here are a few of the most important reference docs:

.. Descriptions here sound like reference

📚 :doc:`/reference/features`
  Overview of all the main features of Read the Docs.

📚 :doc:`/config-file/v2`
  Information for our configuration file: ``.readthedocs.yaml``.

📚 :doc:`/builds`
  Overview of how documentation builds happen.

📚 :doc:`/build-customization`
  Information on how to add your own build logic or replace default build steps.

📚 :doc:`/api/index`
  Automate your documentation with our API and save yourself some work.

