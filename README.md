# NUCLEO-G431RB

1) Certaines broches sont en rouge, d’autres en orange. Pourquoi ?
Les pins marqués en rouge sont réservés pour une fonction particulière, elles ne peuvent/doivent pas être réassignées à d'aurtes usages.

2) Où se situe le fichier main.c ?
Core > Src > main.c

3) À quoi servent les commentaires indiquant BEGIN et END ?
Ils servent à délimiter les zones du fichier où on peut écrire. Sans quoi les lignes entrées seront supprimées au prochain build.

4) Quels sont les paramètres à passer à HAL_Delay et BSP_LED_XXX ? Vous pouvez accéder au code d’une fonction en maintenant la touche <Ctrl> et en cliquant dessus.
On va donner une unité de temps à HAL_Delay. en général 500ms pour faire clignoter notre led 2* par seconde.

      
