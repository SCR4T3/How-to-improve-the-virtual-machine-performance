# How-to-improve-the-virtual-machine-performance
With this configuration you can run your vitual machine 10x faster

1. En la barra de menú de VMware nos vamos a Edit > Preferences > Memory y seleccionamos la opción que dice «Fit all virtual machine memory into reserved host RAM«.

2. Luego en la sección «Priority» elegimos la opción «High» en «Input Grabbed«.

3. Ajustes Terminal
  Primero abrimos la terminal haciendo clic en el menú de Windows, escribimos «cmd» y con clic derecho lo ejecutamos como administrador.
  Hacemos clic en «Si» para conceder los permisos.
  Escribimos en la terminal el siguiente comando: bcdedit /set hypervisorlaunchtype off
  Reiniciamos el equipo.

5. Ajustes de nucleo de Windows 
    Hacemos clic en el menú de Windows y escribimos «Aislamiento del nucleo«.
    En el menú, desactiva la opción «Integridad de memoria«.
    Aceptamos y reiniciamos el equipo.

-- Alejandro Jordán Durán
