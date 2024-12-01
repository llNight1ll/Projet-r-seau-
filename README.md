Mémoire Technique : Proposition et Analyse des Équipements Réseaux
1. Introduction

Ce document fournit une évaluation technique complète pour l'installation des équipements réseau. L'étude inclut les quantitatifs IP, les choix des équipements, ainsi que les analyses de la puissance PoE nécessaire et de la bande passante globale.

2. Quantitatifs IP et Choix d'Équipements
2.1. Sélection des Équipements

La liste complète des équipements figure dans l’Annexe 1.png, située dans le dossier Annexe.

Coûts associés :

    Main-d'œuvre : 5 heures à 300 €
    Coût total après remise : 122 869,40 €
    Économies réalisées : 143 509,80 €

2.2. Plan d’Adressage IP et Configuration des VLANs

Un plan d’adressage IP détaillé a été conçu pour garantir une segmentation optimale du réseau. Chaque VLAN est attribué à un département ou service spécifique, favorisant une gestion efficace de la bande passante et renforçant la sécurité inter-départements.
Pour plus de détails, consulter l’Annexe 2.pdf, située dans le dossier Annexe.

2.3. Configuration et Accès des VLANs

Les configurations des VLANs, y compris les droits d’accès, les interactions entre départements, ainsi que les connexions aux imprimantes, sont disponibles dans l’Annexe 3.pdf, située dans le dossier Annexe. Cette annexe présente en détail la segmentation mise en place et les règles d’accès spécifiques à chaque service.

3. Bande Passante Totale

3.1. Analyse des Résultats par Équipement

Les résultats détaillés concernant l’utilisation de la bande passante par équipement sont disponibles dans l’Annexe 4.pdf, située dans le dossier Annexe.

4. Annexes : Spécifications Techniques des Équipements

OmniSwitch 6860 (OS6860E-P48-EU)

    Ports : 48 ports Gigabit Ethernet
    PoE : Jusqu’à 60 W par port, prenant en charge divers dispositifs tels que les téléphones IP et les points d’accès Wi-Fi.
    Fonctionnalités clés :
        Haute disponibilité pour assurer une fiabilité maximale du réseau
        QoS avancée pour prioriser les types de trafic critique

OmniSwitch 6900 (OS6900T24-F-EU)

    Ports : 24 ports 10-Gigabit Ethernet, idéaux pour les environnements exigeants comme les centres de données
    PoE : Prise en charge de PoE+, offrant une puissance accrue par port
    Fonctionnalités clés :
        Performances élevées avec une faible latence
        Capacité à gérer des volumes importants de trafic

OmniAccess 1411

    Ports : 4 ports Gigabit Ethernet, dont 1 port PoE
    PoE : Jusqu'à 30 W pour alimenter des périphériques compatibles
    Fonctionnalités clés :
        Gestion centralisée de plusieurs points d’accès
        Sécurité renforcée avec WPA3 et 802.1X
        Contrôle d'accès via filtrage MAC et VLAN dynamiques
        QoS permettant de prioriser le trafic voix et vidéo

5. Conclusion

Cette analyse démontre que les équipements sélectionnés répondent parfaitement aux besoins en matière de puissance PoE et de bande passante. Le projet présente un excellent rapport qualité-prix après l’application des remises commerciales. Les calculs confirment que la capacité réseau sera suffisante pour garantir un fonctionnement optimal, fiable et évolutif.
