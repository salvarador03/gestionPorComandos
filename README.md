# gestionPorComandos

Para deshacer un commit en Git, puedes usar el comando git reset. Aquí te dejo los pasos:

Deshacer el último commit y conservar los cambios: Puedes usar el comando git reset --soft HEAD~1. Este comando deshará tu último commit pero mantendrá los cambios en tus archivos1.
Deshacer el último commit y eliminar los cambios: Si quieres deshacer tu último commit y eliminar todos los cambios, puedes usar el comando git reset --hard HEAD~12.
Por favor, ten en cuenta que estos comandos afectarán a tu repositorio local. Si has hecho push de tus cambios a un repositorio remoto, necesitarás forzar el push para reflejar estos cambios.
