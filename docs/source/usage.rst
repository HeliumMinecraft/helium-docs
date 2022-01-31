Uso
=====

.. _installation:

Instalación
------------

Puedes descargar un mod de ejemplo: https://www.github.com/HeliumMinecraft/helium-example-mod y poner en la consola de comandos gradlew setupMinecraft

.. code-block:: console

 <D:\Helium Mods\helium-example-mod> gradlew setupMinecraft

Creating a mod
----------------

Una vez instalado puedes hacer una clase que diga <Nombre del mod>.java que contenga

.. code-block:: java

public class ExampleMod extends Mod implements ModListener, IMod{





}

Hacer un bloque
----------------

Para hacer un bloque crea una clase que diga <nombre del bloque>.java que contenga


.. code-block:: java


public class ExampleBlock extends Block{

public ExampleBlock(){


}



}






