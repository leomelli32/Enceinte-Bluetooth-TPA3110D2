# Enceinte-Bluetooth-TPA3110D2
Conception d'une enceinte Bluetooth avec un amplificateur TPA3110D2 et un récepteur Bluetooth MH-M18.

## Caractéristiques techniques
- **Amplificateur :** Amplificateur TPA3110D2 de classe D (puissance de 2x15W limité à 8 pour les hauts-parleurs en stéréo)
- **Hauts parleurs :** Hauts parleurs d'une JBL Flip 3 (impédance d'entrée : 4 Ohms; puisance : 8 W)
- **Connectivité :** Récepteur Bluetooth MH-M18 géré par un diviseur de tension
- **Alimentation :** Pack Lithium-ion 3S (11.1V nominal) avec protection BMS et recharge USB-C via OT8228

## Paramétrages
- **Limitation de puissance :** Fonction PLIMIT de l'amplificateur, tension fixée à 2,19 V
- **Gain :** réglé à valeur minimale de 20 dB
- **Filtrage :** Filtre LC de sortie (15µH / 2.2µF) avec fréquence de coupure à 27 kHz.
- **PCB :** 4 couches : 1,2,4: GND; 3: Alimentation 12 V
