# Repo de l'equipe des cools
## Participants a la toulouse Robot Race (2022 - 2024)

![image](https://github.com/CedricChauvet/Robotique_et_robots/assets/16280142/7a96cdfc-2575-4e30-9adf-6af0178f3f4b)

 Robot T-rot :
 2 moteurs, 2 télémetres et 2 odométries.
 
 Ce robot a 2 capteurs situé sur la partie latérale droite a pour but de suivre la bordure du circuit.
 
 1 particpation

## Sommaire

 [T_REX](https://github.com/CedricChauvet/Robotique_et_TRR2024/tree/main/T_REX)

 [T_ROT](https://github.com/CedricChauvet/Robotique_et_TRR2024/tree/main/T_ROT)








Contient 3 programmes pour son fonctionnement,


  -TROT MKR_V1  assure le pilotage et l'enegistrement sur une carte SD incluse dans l'arduino MKR
  
  
  -copy_file_to_serial assure la transmission de la carte SD vers l'ordinateur via le bus Serial
  
  -Arduino to script python lit les données arrivant de l'arduino pour les afficher a l'ecran

  
![image](https://github.com/CedricChauvet/Robotique_et_robots/assets/16280142/5e54cd1c-4bbd-4c4a-ab1f-c16b9fdd1735)






Le T-Rot est un robot roulant a 3 roues, il se déplace grace a 2 moteurs asservis en PWM. Sa fonction est de suivre une bordure.
Il inclue un arduino MKR Zero, 2 telemetres positionnés à gauche du chassis ainsi qu'un gyroscope.
