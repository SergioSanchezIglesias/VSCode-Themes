# VSCode-Themes

Repositorio para guardar los disitntos themes personalizados para VSCode.

Para poder usar uno, hace falta abrir **_Visual Studio Code_**. Una vez dentro se deben seguir los siguientes pasos:

1. Abrir la paleta de comandos con `Ctrl + Shift + P`.
2. Buscar por el término `Preferences: Open User Settings (JSON)`.
3. Una vez seleccioanda la opción, se abrirá el archivo **_settings.json_**.
4. Si es la primera vez que personalizamos el theme, basta con copiar los objetos `workbench.colorCustomizations` y `editor.tokenColorCustomizations` del theme que más te guste y pegarlos al final de este JSON, justo antes del cierre de llaves del mismo (**_Importante añadir una `,` al final del último objeto declarado en `settings.json`_**). En caso de que estés utilziando otro theme, debes sustituar los objetos anteriores por los nuevos.
5. Guardar el archivo y visualizar el nuevo theme.
