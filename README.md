# 🌊 Dashboard PoolMaster V1.0 : Gestion complète pH/ORP, Filtration & Consommables

Version 1.0 de mon tableau de bord pour la gestion de piscine (basé sur PoolMaster / ESPHome). L'objectif était d'avoir une interface à la fois belle (WAF compatible), lisible sur mobile, et sécurisée.

Les fonctionnalités clés :

  * Lecture rapide : Jauges colorées pour pH et ORP avec zones de confort.
  * Indicateurs Intelligents (Feux Tricolores) : Visualisation immédiate de l'état des régulations (🔴 Arrêt / 🟠 Veille avec cadenas / 🟢 Auto).
  * Suivi des consommables : Calcul automatique en temps réel des quantités injectées (en mL ou Litres) basé sur le débit des pompes.
  * Sécurité : Les indicateurs d'état sont verrouillés (non-cliquables) pour éviter les fausses manipulations.
  * Menu Admin caché : Un mode "Réglages Avancés" masque toute la configuration technique (PID, calibration, seuils d'alertes, acquittement des erreurs) pour ne pas polluer l'affichage quotidien.
  * Historique : Graphiques de tendances et timeline des injections.
  * Portabilité: Le dashboard utilise les entités créées par Poolmaster. Il ne devrait donc pas y avoir de problème de compatibilité.
  * Compatible mobile: Pour que votre piscine vous suive partout dans votre poche !

# 🛠 Prérequis (à installer via HACS) : Pour que ce code fonctionne, vous devez avoir installé ces 3 cartes personnalisées :
  * Mushroom Cards (pour l'interface principale).
  * Mini Graph Card (pour les courbes).
  * Card Mod (indispensable pour les animations des pompes et le style CSS avancé).

    Problèmes connus:
  * Le % restant de produits affiche des valeurs abérentes
  * L'affichage du fonctionnement des pompes n'est pas "sur" le graph mais en dessous. Je n'ai pas encore trouvé comment faire.
  * Je n'ai pas implémenté l'électrolyseur.
  * A vous de me dire ?

<img width="516" height="1366" alt="Capture d&#39;écran 2026-02-18 225453" src="https://github.com/user-attachments/assets/c474dbdb-9b0e-4166-bcd8-a7fff4b514a0" />
<img width="519" height="622" alt="Capture d&#39;écran 2026-02-18 225521" src="https://github.com/user-attachments/assets/ad6b5e25-e8ab-4849-aa8f-baf2145f77fe" />
<img width="521" height="900" alt="Capture d&#39;écran 2026-02-18 225506" src="https://github.com/user-attachments/assets/a52d9a0c-af7e-48f2-9d10-91bfc4be291e" />
<img width="524" height="371" alt="Capture d&#39;écran 2026-02-18 225514" src="https://github.com/user-attachments/assets/250b9a69-3860-4c26-8e88-bfc9a14bce55" />
<img width="520" height="575" alt="Capture d&#39;écran 2026-02-18 225529" src="https://github.com/user-attachments/assets/bb3c8eff-ab97-42ec-a3ca-696aa41394f4" />
