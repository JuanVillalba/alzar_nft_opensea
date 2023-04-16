# Alzar-NFT-Opensea

Un IDE de Python multiplataforma que implementa Selenium 4.
Si desea apoyar este proyecto o apoyarme a mí, consulte mis NFT https://opensea.io/es/collection/anime-ecchy-ia y desee darle un poco de amor o agarrarlo.
Gracias.

# Descargo de responsabilidad
Este script de versión gratuita no recopila ni captura ninguna información mientras se ejecuta. Asegúrese de comprender toda la codificación y el proceso antes de ejecutar, lea línea por línea el código original antes de comenzar a ejecutar. No seremos responsables de ninguna pérdida y/o daño por el uso de nuestro script. Úselo bajo su propio riesgo.

# Registro de Cambios
<ul>
<li><b>Versión 2.0.1 (subir_2captcha_V2.py)</b><BR>
Se eliminaron algunos controles que ya no eran necesarios para el polígono.<BR>
Se agregó la última versión estable: ChromeDriver
</li>
<li><b>Versión 2.0.0 (subir_2captcha_V2.py)</b><BR>
2Captcha y Buster Solver combinados en un archivo<BR>
Se agregaron verificaciones de errores repetitivas para muchos posibles errores que pueden ocurrir en el sitio<BR>
Se agregó "chrome_extension". Abra la carpeta chrome_extension y lea las instrucciones<BR>
Collection Scraper añadido como prototipo.
</li>
<li><b>Versión 1.9.0 (subir_2captcha.py)</b><BR>
2Resolver captcha<BR>
https://chrome.google.com/webstore/detail/2captcha-solver/ifibfemgeogfhoebkmokieepdoobkbpo?hl=es<BR>
Obtenga su clave API de <a href="https://2captcha.com?from=13605454" target="_blank">2captcha.com</a><BR>
Habilitado y resuelto automáticamente reCaptcha V2 en la página de opciones.
</li>
<li><b>Versión 1.8.9 (subir_captcha.py)</b><BR>
Selección de rango de duración fija
</li>
<li><b>Versión 1.8.8 (subir_captcha.py)</b><BR>
Agregue la extensión de cromo: Buster: Captcha Solver for Humans<BR>
https://chrome.google.com/webstore/detail/buster-captcha-solver-for/mpbjkejclgfgadiemmefgebjfooflfhl?hl=es<BR>
configuración de la extensión: seleccione cualquier "servicio de voz" y coloque la clave API (apoyo visual mas abajo)</ul></li>
<li><b>Versión 1.8.1 (subir18.py)</b>
<ul><li>Admite el formato de metadatos de "atributos" y "propiedades"</li>
</ul></li>
<li><b>Version 1.8 (subir18.py)</b>
<ul><li>Se agregó soporte de duración. La duración máxima es de 6 meses. <BR>
*Por favor, instale el formato de fecha de PC "pip install python-dateutil" <BR>
DEBE establecerse en mm/dd/aaaa
</li>
</ul></li>
 <li><b>Versión 1.0 (subir.py)</b>
<ul><li>Versión estándar</li></ul>
</li>
 
# Instrucciones
<li>Descargue y extraiga este proyecto en su dispositivo local (mantenga todos los archivos y carpetas que vienen con el repositorio en esta carpeta)</li>
<li>Descargue y actualice Python. Mi versión de Python es 3.8.10 * </li>
<li>Coloque todas las imágenes de NFT en la carpeta "src/images" (etc. 1.png), y el archivo .json de metadatos de propiedades de NFT en la carpeta src/json. (etc. 1.json)</li>
<li>Abra esta carpeta de proyecto con cualquier editor de código y haga clic en "abrir powershell" o "Terminal"</li>
<li>Pip install requisitos.txt ejecutando el siguiente comando (pip install -r requisitos.txt) <BR>
Instale PIP para Python si "pip no se reconoce como un comando interno o externo</li>
<li>Ejecute el script, escriba "python upload.py"</li>
<li>Una vez que se ejecute el script, aparecerá la aplicación</li>
<li>Complete la variable para las propiedades de carga de su proyecto, </li>
