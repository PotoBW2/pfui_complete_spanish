# pfUI

Un complemento para World of Warcraft: Vanilla (1.12.1), que pretende ser un reemplazo completo de la interfaz original. El diseño está inspirado en varias capturas de pantalla que he visto de TukUI, ElvUI y otros. Este complemento ofrece funciones modernas y un estilo minimalista que es fácil de usar desde el principio. Está escrito completamente desde cero sin incluir complementos o bibliotecas de terceros.

No se trata de un paquete de complementos como [ShaguUI](http://shagu.org/ShaguUI/), sin embargo, hay soporte para complementos externos como MobHealth3, DPSMate y otros, pero nunca se enviarán dentro del paquete.

**No vuelvas a cargar ni a distribuir versiones obsoletas de este proyecto. Sin embargo, eres más que bienvenido a bifurcar o vincular a la página oficial de Github.**

## Capturas de pantalla

<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI/config.jpg" align="right" width="48.5%">
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI/unlock.jpg" width="48.5%">
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI/contrib.jpg" align="right" width="48.5%">
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI/maraudon.jpg" width="48.5%">

## Instalación
1. Descargar **[Última versión](https://github.com/shagu/pfUI/archive/master.zip)**
2. Descomprima el archivo Rar
3. Copia "pfUI" dentro de Directorio-WoW\Interface\AddOns
4. Reiniciar Wow



## Commands

    /pfui         Abra la GUI de configuración
    /share        Abrir el cuadro de diálogo de importación/exportación de configuración
    /gm           Abrir el cuadro de diálogo de ticket
    /rl           Recargar toda la interfaz de usuario
    /farm         Activa o desactiva el modo Farmeo
    /pfcast       Lo mismo que /cast pero para pasar el mouse sobre las unidades
    /focus        Crea un marco de enfoque para el objetivo actual
    /castfocus    Lo mismo que /cast pero para el marco de enfoque
    /clearfocus   Limpia el marco de enfoque
    /swapfocus    Alternar enfoque y marco de destino
    /pftest       Alternar modo de prueba de marco unitario pfUI
    /abp          Panel de botones complementarios


## Complementos recomendados
* [pfQuest](https://github.com/PotoBW2/pfQuest_complete_spanish) Una base de datos sencilla y un asistente de misiones.
* [ShaguInventory](https://github.com/PotoBW2/ShaguInventory_Complete_Spanish) Este complemento muestra la cantidad de elementos que tienes en todos los personajes (en toda la cuenta) como información emergente.
* [ShaguKill](https://github.com/PotoBW2/shagukill_complete_spanish) Muestra el recuento de muertes restantes u otros eventos que otorgan experiencia que se requieren para alcanzar el siguiente nivel.
* [ShaguScore](https://github.com/PotoBW2/ShaguScore_Complete_Spanish) Este complemento es una clasificación de objetos similar a GearScore.

## Complementos
* [pfUI-eliteoverlay](https://shagu.org/pfUI-eliteoverlay) Añadir dragones de élite a los marcos de unidades
* [pfUI-fonts](https://shagu.org/pfUI-fonts) Fuentes adicionales para pfUI
* [pfUI-CustomMedia](https://github.com/mrrosh/pfUI-CustomMedia) Texturas adicionales para pfUI
* [pfUI-Gryphons](https://github.com/mrrosh/pfUI-Gryphons) Vuelve a agregar los grifos a tus barras de acción

## FAQ
**¿Qué significa "pfUI"?**  
El término "*pfui!*" es alemán y simplemente significa "*pooh!*", porque no soy
un gran fanático de crear interfaces de usuario de configuración, especialmente no a través de Wow-API
(quizás hayas notado eso en ShaguUI).

**¿Cómo puedo donar?**  
Puedes donar a través de [GitHub](https://github.com/sponsors/shagu) o [Ko-fi](https://ko-fi.com/shagu) al editor original.

Puedes donar a través de "*Paypal*" a joseamosher@gmail.com por mis trabajos de traducción.


**¿Cómo puedo informar un error?**  
Proporcione la mayor cantidad de información posible en el [Bugtracker](https://github.com/shagu/pfUI/issues).
Si hay un mensaje de error, proporcione el contenido completo. Simplemente decir que "hay un error" no ayudará a ninguno de nosotros.
Considere agregar información adicional como: desde cuándo recibió el error,
¿sigue sucediendo con una configuración limpia?, ¿qué otros complementos están cargados y qué versión está ejecutando?
Al jugar con un cliente que no está en inglés, el idioma también puede ser relevante. Si es posible, explique cómo las personas pueden reproducir el problema.

**¿Cómo puedo contribuir?**

Informa errores y problemas en el [Bugtracker](https://github.com/shagu/pfUI/issues).
Asegúrate de tener instalada la última versión y comprueba de antemano si hay complementos conflictivos.

**Tengo un mal rendimiento ¿qué puedo hacer?**  
Solo hay un problema de rendimiento conocido: se produce al usar "Sombras de marco". Asegúrate de desactivarlas
en la configuración de pfUI (Configuración -> Apariencia -> Activar sombras de marco). Si sigues teniendo un rendimiento bajo,
es muy probable que se deba a una combinación con otro complemento. Desactiva todos los complementos excepto pfUI y luego habilítalos uno por uno,
hasta que el problema de rendimiento vuelva a ocurrir. Asegúrate de informar el complemento identificado y lo que hiciste para reproducirlo
a través del [Bugtracker](https://github.com/shagu/pfUI/issues).

**¿Dónde está el indicador de felicidad de las mascotas?**  
La felicidad de la mascota se muestra en el color del marco de la misma. Según su piel, puede ser el texto o el color de fondo de la barra de salud de su mascota:

- Verde = Feliz
- Amarillo = Normal
- Rojo = Infeliz

Desde la versión 4.0.7 también hay un ícono adicional que se puede habilitar desde las opciones del marco de la unidad de mascota.
 
**¿Puedo usar Clique con pfUI?**  
Este complemento ya incluye compatibilidad con clickcasting. Si aún desea utilizar Clique, todos los marcos de unidad de pfUI ya son compatibles con Clique. La versión compatible con pfUI se puede encontrar [Aquí](https://github.com/shagu/Clique/archive/master.zip). Si desea conservar su versión actual de Clique, deberá aplicar este [Parche](https://github.com/shagu/Clique/commit/a5ee56c3f803afbdda07bae9cd330e0d4a75d75a).

**¿Dónde está la Barra de Experiencia?**  
La barra de experiencia aparece al pasar el mouse sobre ella y cada vez que obtienes experiencia, junto al marco de chat izquierdo de manera predeterminada. También hay una opción para que permanezca visible todo el tiempo.

**¿Cómo muestro el Dock del medidor de daños y amenazas?**  
Si habilitó la función "dock" para sus medidores externos (de terceros) como DPSMate o KTM, entonces podrá alternar entre ellos y el Chat derecho haciendo clic en el símbolo ">" en el panel inferior derecho.

**¿Por qué mi chat siempre se restablece a solo 3 líneas de texto?**  
Esto sucede si la opción "Chat simple" está habilitada en la configuración de la interfaz de Blizzard (Opciones avanzadas). Pegue el siguiente comando en su chat para deshabilitar esa opción: `/run SIMPLE_CHAT="0"; pfUI.chat.SetupPositions(); ReloadUI()`

**¿Cómo puedo habilitar el casteo al pasar el mouse por encima?**  
En Vanilla, crea una macro con "/pfcast SPELLNAME". Si también quieres ver el tiempo de recuperación, puedes agregar "/run if nil then CastSpellByName("SPELLNAME") end" encima de la macro.

**¿Habrá pfUI para los remakes "clásicos" de Activision?**  
No, sería necesario reescribir por completo el AddOn, ya que ahora el juego es diferente. La API de AddOn ha evolucionado durante los últimos 15 años y las nuevas versiones "Clásicas" se basan en un cliente de juego actual. No tengo pensado jugar a ninguna de esas nuevas versiones, por lo que no voy a adaptar ninguno de mis complementos a ella.

**¡Todo desde cero! ¿Estás loco?**  
Lo más probable es que sí.
