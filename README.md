# Planiftel – architecture réseau pour des objets connectés  

**Contexte** :  
Ce projet académique vise à comparer les performances des différentes technologies de transmission (4G/5G, câbles coaxiaux, fibres optiques) pour des applications de télécommunications haut débit. L'étude inclut des calculs théoriques, des simulations et des mesures pratiques pour évaluer les paramètres clés comme le débit, l'atténuation, la portée et le coût.  

**Méthodologie** :  
1. **Technologies Sans Fil** :  
   - Analyse des débits théoriques (4G : 150 Mb/s) et des contraintes de couverture.  
   - Mesures terrain avec l'application NetMonster (RSSI, PIRE) autour de l'ISEP.  
   - Calculs de zones de sécurité et de puissance d'émission (ex : PIRE = 101.06 dBm).  

2. **Technologies Filaire** :  
   - Comparaison détaillée des câbles coaxiaux et fibres optiques (monomode/multimode) :  
     - **Bande passante** : Jusqu'à 10 GHz pour la fibre monomode.  
     - **Atténuation** : 0.2 dB/km (monomode) vs 3.5 dB/km (coaxial).  
     - **Portée maximale** : 477 km (monomode) vs 28 km (coaxial).  
   - Calcul du RSSI nécessaire pour un débit de 1 Gb/s (ex : -85.4 dBm pour la fibre monomode).  

3. **Dimensionnement** :  
   - Recommandation de la **fibre monomode** pour des liaisons >50 km (coût : 618€/km, sans répéteurs).  

**Outils Utilisés** :  
- **Simulation** : MATLAB, LTSpice.  
- **Mesures** : NetMonster (Android), calculs manuels (formules Shannon-Hartley).  
- **Cartographie** : Cartoradio.fr pour l'analyse des stations de base.  

**Résultats Clés** :  
- La fibre monomode est optimale pour les longues distances (faible atténuation, haut débit).  
- Les câbles coaxiaux sont limités par leur portée et leur bande passante.  
- La 4G reste préférable à la 5G dans les zones à couverture limitée.  

**Perspectives** :  
- Intégration des calculs dans un script Python pour automatiser l'analyse.  
- Extension aux réseaux 6G et aux fibres optiques avancées (e.g., multicœur).  
```

**Mots-Clés** :  
`#Telecom #4G #5G #FiberOptic #Coaxial #ShannonHartley #RSSI #NetMonster #LTSpice`  
