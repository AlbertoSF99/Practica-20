# Práctica 20 - Detector de galaxias, nebulosas y planetas

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 3 - Sesión 8

En esta práctica se realizó con Custom Vision una forma de detectar planetas, nebulosas y galaxias a partir de imágenes las cuales analizaba para detectar similutudes de acuerdo a los tags que le dieramos. 

------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.

-------------------------------------------------------

#### Pasos a seguir

1. Accedemos a la siguiente página: [https://www.customvision.ai/](https://www.customvision.ai/) y nos logueamos con la nuestra cuenta. Una vez habiendo ingresado, le damos en ‘New Project’ y llenamos los datos solicitados. En caso de no tener creada un grupo de recursos, le damos entonces a ‘Create now’. Llenamos los datos requeridos para la creación del grupo de recursos y en ‘Kind’ escogemos ‘CognitiveServices’.

![P20I1](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2001.PNG)

![P20I2](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2002.PNG)

2. Una vez creado el recurso, en la primera ventana que teníamos vamos a elegir el recurso previamente creado e inmediatamente desplegará más opciones, como ‘Project Types’, ‘Clasification Types’ y ‘Domains’. En Domains preferiblemente escogemos ‘General [A2]'. Una vez habiendo configurado estas opciones, le damos en ‘Create project’.

3. Al haberse creado el proyecto, nos mostrará la opción de agregar imágenes. Podremos agregar un conjunto de imágenes y ponerles un ‘Tag’ que corresponda con el contenido de la imagen. Una vez habiendo agregado el conjunto de imágenes (Galaxia, nebulosa, planeta) es necesario agregar un conjunto de imágenes con un Tag negativo, esto, para discernir de imágenes que contengan información que no sean de nuestro interés (para este ejemplo, estrellas).

![P20I3](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2003.PNG)

![P20I4](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2004.PNG)

4. Habiendo realizado el paso anterior, podremos poner a entrenar a la inteligencia artificial al darle en ‘Train’ y ‘Quick Training’ y esperamos a que termine de entrenar. Una vez terminado, podremos ponerlo a prueba a través de la opción ‘Quick Test’ y pegamos el link de alguna imagen (o podemos subirla de nuestros archivos locales) y la analizamos. Arrojará los resultados en forma de lista de los tags con el porcentaje de aproximación.

![P20I5](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2005.PNG)

![P20I6](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2006.PNG)

![P20I7](https://github.com/AlbertoSF99/Practica-20/blob/main/Images/Sesi%C3%B3n%208%20-%20P20%2007.PNG)

***Información Adicional:*** Se puede volver a ingresar imágenes y entrenar para mejorar la IA. En ‘Probability Threshold’ podremos “calibrar” el desempeño de la IA.
