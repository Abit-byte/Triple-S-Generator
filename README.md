# Triple-S Generator
Un générateur de fonctions analogique compact, construit autour de l'amplificateur opérationnel TL072IP, capable de produire des signaux sinusoïdal, en dent de scie et carré.

---

### Caractéristiques :
- Trois formes d'onde simultanées : sortie sinusoïdale, dent de scie et carrée, sélectionnables via les commandes en façade
- Large plage de fréquences : condensateurs de calibrage commutables (3.3µF / 33nF / 330pF) couvrant environ 1.5 Hz à 150 kHz
- L'option de modifier le temps de montée et de descente, l'amplitude et la composante continue du signal avec des potentiomètres
- Alimentation symétrique ±9V pour des signaux de sortie centrés et propres
- Construction en traversant (THT) avec des composants largement disponibles (TL072IP, diodes 1N4148, composants passifs standards)
- PCB 2 couches avec plan de masse en cuivre pour réduire le bruit
- Connecteurs à vis pour l'alimentation et la sortie signal

### Détails de conception :
- U1 gère l'oscillateur à trigger de Schmitt et l'étage intégrateur (génération du carré et de la dent de scie)
- U2 gère la mise en forme du signal sinusoïdal et le buffer de sortie
- Le réseau de diodes (D1–D4) assure la mise en forme du signal sinusoïdal
- Des commutateurs SP3T permettent de sélectionner la forme d'onde et la plage de fréquence
- Conçu et routé sous KiCad, fabriqué via JLCPCB

---

## Photos de résultats

> Vous pouvez les trouver aussi dans la dossier *photos-of-final-result*.

| Schémas  | PCB |
| :-----------: | :-----------: |
| ![Schémas](...)  | ![PCB](...)  |

---

> [!NOTE]
> Une Intelligence Artificielle a été utilisée uniquement pour rédiger ce texte README.
