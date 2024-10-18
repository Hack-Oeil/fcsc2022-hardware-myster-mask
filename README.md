# FCSC 2022 Myster Mask

Myster Mask a conçu une implémentation qui craint un max !

Vous allez devoir analyser les traces de consommation d’un début d’implémentation de l’AES faite par Myster Mask. Saurez-vous exploiter ces traces pour faire la différence ?

La partie à cibler correspond à l’étape d’**inversion** présente dans le calcul de la boîte S dans le premier tour de l’AES. **Seule cette étape est implémentée**, il n’est pas necessaire de connaître l’AES puisque ce challenge est spécifiquement centré sur l’étape d’inversion.

Les traces de consommation fournies dans le fichier ```traces.npz``` à charger avec ```numpy``` correspondent à la ligne suivante dans le code ```myster_mask.py``` :

<code>
masked_inversion(L)
</code>

Attention, en tant que bon détective, Myster Mask a protégé cette inversion en faisant honneur à son nom. À vous de jouer !


Fichiers :

Fichiers :
- [output.txt](output.txt) 
- [myster_mask.py](myster_mask.py) 
- [inputs.npz](https://hackropole.fr/challenges/fcsc2022-hardware-myster-mask/public/inputs.npz)
- [traces.npz](https://hackropole.fr/filer/fcsc2022-hardware-myster-mask/public_filer/traces.npz)



Auteurs : Mélissa et Ange

Origine : [Myster Mask](https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-myster-mask/)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-hardware-myster-mask.git

> cd fcsc2022-hardware-myster-mask


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-myster-mask/