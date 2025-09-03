# Entrega-2---Emiliano-Qui-ones
Entrega del proyecto N° 2 Fast Prompting en Acción - Emiliano Daniel Quiñones - Comisión 86075


Presentación del Problema a abordar

En mi emprendimiento ArtePads, la cual se dedica al diseño y venta de mousepads personalizados, recibo constantemente consultas de clientes a traves de las distintas redes sociales. Las mismas se suelen repetir bastante: medidas disponibles, materiales, precios y como varían según el tamaño, formas de envio, formas de pago, como cargar diseños propios y modificarlos, etc.

Actualmente estoy respondiendo las dudas manuelamente, pero me consume mucho tiempo y retrasa las respuestas, lo cual puede afectar la experiencia del cliente y hacerme perder posibles ventas.

El problema que identifico es la falta de automatizacion en la atencion al cliente. Resulta fundamental desarrollar una solucion ya que:

  	Los clientes esperan respuestas claras y rápidas 
  
  	Una atención eficiente mejora las ventas 
  
  	Resolver el problema permitiría que las ventas escalen sin depender de la disponibilidad horaria
  


DESARROLLO DE LA PROPUESTA DE SOLUCIÓN

La solución será el desarrollo de un chatbot inteligente basado en prompts, capaz de resolver consultas frecuentes y que ayude a los clientes en el proceso de compra.

El chatbot integrará dos modelos de IA:
  	Texto-texto: La IA (como ChatGPT) responderá preguntas, tales como: medidas, materiales, precios, tiempos de entrega y     los limites de la personalización, etc.
  Los prompts que el chatbot desarrollaría serían:
  
  •	“Eres un asistente de ArtPads. Responde de forma clara y breve las consultas de los clientes sobre medidas, precios,       materiales, tiempos de entrega y formas de pago. Usa un tono cordial y profesional.”
      
  •	“Eres un asistente de ArtPads: El cliente pregunta “[pregunta que hizo el cliente]”. Formula la respuesta utilizando       los siguientes datos:
  [tabla con datos sobre los productos]
  Responde de manera cordial y profesional.”
      
  •	“Si un cliente describe un diseño, ayudalo a expresarlo mejor para poder generarlo en una imagen. Luego formula un         prompt descriptivo que pueda usarse en una herramienta de IA de generación de imágenes.”
      
  	Texto-imagen: Se generarán imágenes de mousepads personalizados, que permitirá que el cliente tenga una mejor idea de      como se verá el producto.
  
  Los prompts que generará el chatbot serán:
  
  •	“Genera la imagen de un mousepad rectangular de [Largo x Ancho] cm con un diseño [insertar la descripción del diseño       que se generó anteriormente”.

      
JUSTIFICACIÓN DE LA VIABILIDAD DEL PROYECTO

El proyecto es altamente viable debido a:

  	Tengo acceso a herramientas de IA (como ChatGPT) para pruebas de prompts de texto y con herramientas gratuitas de         generación de imágenes como Nightcafe (para la parte visual).
  
  	No lleva mucho tiempo, el prototipo puede desarrollarse por etapas, es decir, primero comenzará con prompts para las       preguntas frecuentes (texto) y luego extendiéndolo a la generación de imágenes
  
  	Como se basa en prompts, no requiere programación avanzada ni infraestructura compleja en la fase inicial. Luego, se        puede integrar este chatbot a redes como WhatsApp, Instagram o la web del emprendimiento.
  
  
En conclusión, el proyecto es viable, además de tener una aplicación práctica inmediata en un negocio real.
