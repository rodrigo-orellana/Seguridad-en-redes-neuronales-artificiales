[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  
<p align="center">
  <img src="/img/banner-01.png" alt="Seguridad en redes neuronales artificiales" >
</p>


<p align="justify"> 
Las redes de aprendizaje profundo en inteligencia artificial han destacado en la última década con resultados sorprendentes en aplicaciones como visión artificial, conducción automática de vehículos, detección de fraudes bancarios, interpretación de comandos de voz, filtrado de seguridad de redes y otros más,  abriendo paso a una nueva era a nivel tecnológico. Sin embargo, han surgido muchas investigaciones en busca de brindar seguridad en su operación, debido a que se ha descubierto que dichas redes son vulnerables en cuanto a sus resultados entregados cuando una entrada ha sido adulterada de manera imperceptible a una revisión humana. Este ejercicio es llamado ataque adversario, en donde el atacante busca hacer fallar la clasificación o incluso dirigirla a hacia una respuesta deseada. Esto implica un riesgo en la aplicación de esta tecnología que incluso puede suponer riesgos de vidas humanas, economías de países o de la privacidad de las personas. Actualmente este es un incidente abierto, ya que no se ha planteado una solución definitiva para asegurar la robustez de las redes profundas, Sin embargo, han surgido ciertos avances para proteger a los modelos de ciertos tipos de ataques particulares.
El objetivo de este proyecto es en primer lugar realizar un estudio del estado del arte en cuanto a la seguridad de las redes profundas, luego realizar experimentos planteando, ejecutando y analizando resultados de ataques a distintos modelos. Por otro lado, se plantea y experimenta una contramedida que brinda robustez al modelo.
 </p>

<p align="center">
  <img width="460" height="300" src="/img/attack.png">
</p>

<p align="justify"> 
La imagen muestra 6 resultados de ataques exitosos aplicados en un modelo CNN de identificación de placas matrículas, en donde se emplean pequeñas alteraciones a él dígito "uno" para que sea clasificado como un número distinto.
 </p>

 # Experimentos: Jupyter Notebook  
 ## Adversarial Attack  
* [Adversary Attack en Fashion MNIST: Transferibilidad Adversarial Attack](/src/adversarie_attack_fashion_mnist.ipynb)
* [Adversary Attack en MobileNetV2 y ImageNet: Señales de tránsito](/src/Adversary_Attack_MobileNetV2_ImageNet.ipynb)
* [Adversarial Attack Placa de Matrícula alemana: Ataque digital](/src/Matricula%20ataque%20físico.ipynb)
* [Adversarial Attack Placa de Matrícula alemana: Ataque físico](/src/Matricula%20ataque%20físico_impreso.ipynb)  
* [Adversarial Attack Placa de Matrícula española: Ataque digital](/src/Matricula%20española%20ataque%20físico.ipynb)  

## Experimentos de robustez  
### Matrícula alemana 

* [CNN Defensa 01](/src/defenza_adversarial_attack_digito_uno_intento1.ipynb)
* [CNN Defensa 02](/src/defenza_adversarial_attack_digito_uno_intento2.ipynb)
* [CNN Defensa 03](/src/defenza_adversarial_attack_digito_uno_intento3.ipynb)
* [CNN Defensa 04](/src/defenza_adversarial_attack_digito_uno_intento_4.ipynb)  
  
<p align="center">
  <img width="800" height="240" src="/img/tabla_defensas02.PNG">
</p>
  
### Matrícula española

* [CNN Defensa 03](/src/defenza_adversarial_attack_digito_uno_intento3-ESP.ipynb)  
  
<p align="center">
  <img width="800" height="150" src="/img/tabla_defensas02_esp.PNG">
</p>


https://github.com/sergiomsilva/alpr-unconstrained
https://github.com/quangnhat185/Plate_detect_and_recognize



<p align="center">
  <img src="/img/banner-02.png">
</p>
