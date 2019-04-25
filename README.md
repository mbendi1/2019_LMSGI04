# 2019_LMSGI04
## Chatbot amb AIML
Un dels dialectes d'XML és AIML, que significa llenguatge de marques per a la intel·ligència artificial. Amb AIML es pot definir el comportament de bots conversacionals, chatbots.

En aquesta tasca realitzarem dos chatbots. El primer d'ells tendrà com a punt de partida un exemple d'informació turística en anglès disponible al tutorial de Steve Worswick. Implementau-lo a la plataforma pandorabots.com traduït a una altra llengua (en principi català o espanyol; si ho voleu fer en alguna altra, parlem-ne).

Per al segon chatbot, triau un tema que us interessi i desenvolupau una aplicació pròpia. Si voleu, poden ser modificacions substancials o ampliacions d'algun dels exemples disponibles al repositori https://github.com/pandorabots/Free-AIML.

Què s'ha de lliurar?
L'adreça URL del vostre repositori amb els dos fitxers de marques .aiml.

Com s'avalua?
Cada chatbot obté un màxim de 5 punts, d'acord amb els següents ítems.

1 punt. Ús de més de deu categories.
1 punt. Ús de context.
1 punt. Complexitat i originalitat de la vostra aplicació.
1 punt. Utilització d'altres fitxers que es poden definir a pandorabots, a més del .aiml.
1 punt. Realització de vídeo amb converses reals que demostrin les capacitats dels vostres bots.

Tot i que hi ha temps fins a final d'abril per a realitzar els dos bots, convé tenir enllestit el primer en unes cinc setmanes, cap al 15 de març.

# lmsgi
Se trata de la traducción al castellano del tutorial de Steve Worswick.
Responde a las preguntas:
- Hablame sobre ....
- Que tiempo hace en ....
- Muestrame un mapa de ...
Y, responde a las mismas preguntas, pero en vez de poner el lugar, decimos "allí".
Además, en el caso de introducir la ciudad en minúsculas, devuelve el resultado con la primera letra de la ciudad en mayúsculas.

En el archivo, **video_ejemplo.rar** se encuentra el video que muestra el funcionamiento del bot.

# marcosasiste
Proyecto de chatbot de asistencia Técnica al usuario sobre:
- **Hardware.** Muestra información básica sobre fallos comunes de hardware, e información de contacto con personal del CAU.
- **Software.** Muestra como ponerse en contacto con el CAU para que personal autorizado proceda a la revisión del software. 
- **Gestión de Contraseñas.** Asistencia para cambiar y recuperar contraseñas de usuario en diferentes sistemas.

Para repartir el código, y para poder emplear diferentes módulos en otros posibles futuros proyectos, se ha separado el archivo en lo siguiente:
- Un archivo **udc.aiml** que sería algo así como el menu principal y el que carga el resto de los módulos.
- Un archivo **passwords.aiml**, que contiene el apartado de asistencia en lo referente a contraseñas.
- Un archivo **saludos.aim**l, que contiene lo referente a saludos, como hola o buenos días; y tambien Gracias o Adiós. muy básico.
 -Un archivo **software.aiml** donde se pretenderán solucionar las diferentes consulatas sobre el software que pueda tener instalado la organización.
- Un archivo **hardware.aiml** para resolver las consultas sobre hardware.
- Archivo **ciudades.aiml** Referente a una consulta sobre el apartado otro softwarte (software.aiml),recogerá la ciudad, y la empleará para obtener del archivo **mapas.set** y **mapas.map** la provincia, devolviéndo esta como parte de un correo electrónico.
En todo ello, se incluyen, texto, inserción de imagen en la ventana del chatbot; botón de enlace a página web externa, enlace a video de youtube.....

En el archivo **video_marcosasiste.rar** se encuentra el video que muestra el funcionamiento del bot.
