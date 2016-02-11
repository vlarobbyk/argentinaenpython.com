.. title: Mapas de OpenStreetMap para Garmin
.. slug: mapas-de-openstreetmap-para-garmin
.. date: 2016-01-14 23:17:00 UTC-03:00
.. tags:
.. category: 
.. link: 
.. description: Mapas de OpenStreetMap para Garmin
.. type: text
.. template: storygarmin.tmpl

.. raw:: html

   <style>
     img.logo {
         margin-top: 20px;
	 max-width: 38%;
     }
   </style>

.. image:: osm.jpg
   :align: right
   :class: logo
   

Estos mapas son una continuación del `trabajo que ha realizado
<http://www.i-nis.com.ar/osm/garmin>`_ [#]_ Martin Andres Gomez Gimenez
`junto con la comunidad
<http://forum.openstreetmap.org/viewtopic.php?id=17139>`_ [#]_ de
`OpenStreetMap <http://openstreetmap.org/>`_ durante los últimos años
para generar mapas para dispositivos Garmin con *nuestros* datos.

Nosotros hemos utilizado estos mapas con el proyecto `Argentina en
Python <http://argentinenpython.com.ar/>`_ por más de 2 años en
Argentina, Uruguay, Paraguay, Bolivia, Chile y Brasil. Sin embargo,
luego de ese tiempo llegamos a Perú y el mapa que Martín genera no
cubre este país. Es por eso que hemos decidido generarlos nosotros
mismos y ponerlos a disposición de ustedes en caso de que les sirvan.

:Archivo: `gmapsupp.img <gmapsupp.img>`_ (para Perú)
:Tamaño: {{size}}
:Fecha: {{date}}
:Copyright: © Colaboradores de `OpenStreetMap`_, `ODbL
	    <http://www.openstreetmap.org/copyright>`_
:MD5: {{md5}}
:SHA1: {{sha1}}
:SHA256: {{sha256}}

Los mapas se actualizan semanalmente mediante una `tarea de CRON
<https://github.com/humitos/garmin-osm>`_ automática y sin supervisión
humana. Por lo tanto si encuentras un problema con el enlace o el
archivo está corrupto por algún motivo, envíanos un `email
<mailto:argentinaenpython@openmailbox.org>`_.

..
   Creado utilizando las siguientes herramientas:

   :mkgmap: {{mkgmap}}
   :splitter: {{splitter}}
   :osmconvert: {{osmconvert}}
   :osmfilter: {{osmfilter}}

.. admonition:: Nota

   Es posible que en un futuro generemos los mismos mapas de otros
   países. Si estás interesado en que generemos los mapas del país en
   el que vives, ponte en contacto con nosotros.

.. [#] Código fuente: https://proyectos.ingeniovirtual.com.ar/projects/garmin-osm
.. [#] En esa discusión hay mucha información sobre cómo funciona el
       mapa internamente y detalles de cómo se tomaron algunas
       decisiones.