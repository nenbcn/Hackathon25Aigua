# **MICA: Monitorización Inteligente del Consumo de Agua**

## **¿Qué es MICA?**

MICA es una solución tecnológica diseñada para abordar los retos del consumo doméstico de agua en entornos urbanos. Combina sensores IoT, inteligencia artificial y una aplicación web/móvil para ofrecer a los ciudadanos una herramienta potente que les permita optimizar su consumo de agua, detectar fugas y adoptar hábitos más sostenibles. Su diseño se basa en un enfoque accesible y abierto, orientado a maximizar el impacto social y ambiental.

## **La necesidad: escasez de agua y falta de datos**

Barcelona, como muchas ciudades mediterráneas, enfrenta sequías cada vez más frecuentes y severas debido al cambio climático. El 70% del consumo de agua en la ciudad es doméstico, y el consumo diario medio por habitante supera los 100 litros, por encima de los límites deseables. Según el IERMB (2020), solo la mitad de los hogares adoptan hábitos responsables y la mayoría desconoce su consumo exacto. Los contadores tradicionales no permiten desglosar el consumo ni ofrecen datos en tiempo real. MICA nace para llenar ese vacío.

## **¿Cómo funciona MICA?**

### **Arquitectura general:**

* **Sensor de caudal**: mide el flujo de agua en tiempo real, usando tecnología de efecto Hall.

* **Unidad de procesamiento**: basada en microcontroladores STM32L0, optimizados para bajo consumo energético.

* **Gateway IoT (ESP32)**: comunica los datos del sensor a la nube usando Wi-Fi o LoRa.

* **Nube (AWS)**: ingestán, almacenan y procesan los datos en diferentes capas.

* **Aplicación web/móvil**: accesible desde cualquier dispositivo, permite ver el consumo en tiempo real y por dispositivo.

### **Inteligencia Artificial:**

MICA aplica un modelo basado en redes neuronales convolucionales y recurrentes (RCNN) que realiza una descomposición temporal del flujo de agua para detectar y clasificar eventos como duchas, cisternas o lavadoras. Esta técnica, inspirada en el NILM del sector energético, se adapta por primera vez al ámbito hídrico.

### **Incentivos y gamificación:**

El sistema incorpora "MICAcoins", puntos que se otorgan por comportamientos sostenibles (reducción de consumo, participación en retos, recomendaciones a otros usuarios). Estos puntos pueden convertirse en donaciones a entidades del tercer sector.

## **Fases del proyecto**

1. **Desarrollo del MVP**: sensor, firmware, IA y app (meses 1-6).

2. **Simulaciones de laboratorio**: validación del sensor y calibración de algoritmos.

3. **Prueba en hogares de confianza**: primera evaluación en condiciones reales.

4. **Programa beta (50-200 hogares)**: evaluación estadística de impacto, reentrenamiento del modelo y mejoras (meses 7-12).

## **Impacto**

### **Ambiental**

MICA permite detectar fugas, reducir el desperdicio y fomentar el ahorro de agua. El objetivo es que al menos el 50% de los usuarios reduzcan su consumo de forma significativa.

### **Social y educativo**

Empodera a los ciudadanos con información personalizada y fomenta una cultura de corresponsabilidad hídrica. Además, la app tiene un enfoque educativo para familias, ayudando a niños y adolescentes a entender el valor del agua.

### **Institucional**

La plataforma puede proporcionar datos agregados en tiempo real a las autoridades municipales, ayudando a optimizar la gestión del agua y a tomar decisiones informadas en contextos de emergencia hídrica.

### **Tecnológico**

Barcelona puede posicionarse como ciudad pionera en el uso de tecnología cívica para la sostenibilidad hídrica, replicando este modelo en otras regiones.

## **Innovación**

* **Tecnología NILM para agua**: primera aplicación en España de esta metodología.

* **Diseño colaborativo**: las carcazas se fabrican mediante impresión 3D distribuida por una red de colaboradores.

* **Open hardware y software**: tanto el diseño del sensor como el código serán publicados para fomentar una comunidad abierta de desarrollo.

## **Comunidad y replicabilidad**

MICA promueve la creación de una comunidad de usuarios y makers que contribuirán a mejorar el producto. La plataforma está diseñada para escalar y adaptarse a otros entornos urbanos o rurales, gracias a:

* Alianzas con empresas de agua (Agbar, CASSA).

* Colaboraciones con fabricantes de contadores (Kamstrup, Diehl).

* Integración en infraestructuras de telelectura.

## **Comunicación y marca**

* MICA cuenta con una identidad visual consistente y clara.

* Web informativa: [mica.eco](https://www.mica.eco/)

* App alojada en Vercel y desarrollada en Next.js.

* Campañas en redes, colaboraciones con entidades locales y participación en ferias tecnológicas.

## **Conclusión**

MICA no es solo un producto, sino una plataforma de transformación ciudadana hacia el uso sostenible del agua. Mediante tecnología accesible, datos accionables y un enfoque comunitario, MICA busca iniciar un cambio profundo y escalable en la relación de las personas con el agua. Con una base sólida, un equipo multidisciplinar y un modelo abierto, aspira a convertirse en un referente de la innovación urbana.

"De MICA en MICA s'omple la pica": pequeños gestos, gran impacto.

