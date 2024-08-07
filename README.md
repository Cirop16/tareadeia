Desarrollarás  una POC (proof of concept) que permita, a través de una jupyter notebook, mostrar una implementación utilizando las técnicas de Fast prompting para solucionar el problema seleccionado.


Introducción:
Nombre del proyecto.
Presentación del problema a abordar: señala el problema elegido para resolver. Desarrolla por qué es una problemática y por qué es relevante desarrollar una solución.
Desarrollo de la propuesta de solución: Indica cómo la solución se vincula al desarrollo de modelos de IA. Describe los prompts que llevarás a cabo para dar respuesta al problema elegido en las siguientes etapas de trabajo.
Justificación de la viabilidad del proyecto: analiza la viabilidad técnica de tu proyecto, teniendo en cuenta el tiempo y los recursos disponibles. Justifica tus elecciones.
Objetivos: Indica los objetivos del proyecto.
Metodología: ¿Cómo se llevará a cabo el proyecto? ¿Qué procedimientos implementados para lograr los objetivos? Justifica tus respuestas.
Herramientas y tecnologías: ¿Qué técnicas de prompting utilizarás? Justifica tus respuestas 
Implementación: Desarrolla el prompt y el código que te permitirá llegar a tu solución propuest

A. nombre del proyecto: un viaje para ti de ia
B. presentación del problema: tengo el tiempo y el dinero para irme de acciones pero tengo el tema de que no me puedo decidir bien porque soy muy desprolijo para eso recurro a la ia para que me de recomendaciones que me puedan gustar acorde a mis gustos
C. desarrollo de la propuesta de solución: se le aclaran las cosas a definir en los siguientes 3 prompts 
prompt = "tengo ganas de ir de vacaciones a la playa y a la vez me gusta hacer turismo dentro del pais"

process_text_to_image = "En base a la historia anterior crea un prompt que pueda generar una imagen que muestre el escenario correspondiente a la playa donde tengo que ir de vacaciones"



image_from_scenario = f"En base a la historia anterior, crea una imagen que represente el escenario descripto: {img_prompt}"

D. justificación de la viabilidad del proyecto: la viabilidad del proyecto es factible, ya que se ahorra en el año para tener la capacidad económica de ir a vacacionar a playas que queden dentro de argentina y además la disponibilidad del tiempo

objetivo: poder dilucidar la selección de una playa para vacacionar, ya que se me hace imposible el tomar una decisión

el proyecto se lleva a cabo dándole una pequeña reseña de lo que me gustaría como destino final para vacacionar y luego en los prompts de modelo de texto-texto y texto-imagen, que explaye destinos e imagenes del destino

como herramienta en esta segunda entrega se utilizo jupyter notebook. Se usó la técnica “one shot prompting” para hacer el trabajo; por su capacidad de maximizar la efectividad de la IA en una cantidad máximas de datos en un solo prompt
