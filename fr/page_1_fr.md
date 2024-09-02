### 1. **Collision avec le sol**
   - **Détection de sol** : Le sprite du joueur détecte lorsqu'il touche le sol, l'empêchant de traverser.
   - **Rebond au sol** : Lorsque le joueur tombe sur le sol, il arrête de descendre et peut marcher ou sauter à nouveau.

### 2. **Collision avec les murs**
   - **Collision horizontale** : Le sprite du joueur s'arrête lorsqu'il entre en contact avec un mur à gauche ou à droite.
   - **Glissement le long des murs** : Le joueur peut glisser contre un mur lorsqu'il est en l'air et qu'il entre en contact avec le mur.
   - **Rebond contre le mur** : Le joueur peut effectuer un "wall jump", rebondissant d'un mur pour atteindre des hauteurs supplémentaires ou changer de direction en l'air.
   - **Escalade de mur** : Le joueur peut grimper ou s'agripper à certains types de murs pour monter plus haut.

### 3. **Collision avec les plafonds**
   - **Détection de plafond** : Empêche le joueur de monter à travers un plafond lorsqu'il saute.
   - **Rebond vers le bas** : Si le joueur heurte un plafond, il est repoussé vers le bas.

### 4. **Collision avec les blocs destructibles**
   - **Destruction de blocs** : Le joueur peut casser certains blocs lorsqu'il saute en dessous ou les touche avec une force spécifique.

### 5. **Collision avec les limites de l'écran**
   - **Limites du niveau** : Le joueur ne peut pas sortir de la zone de jeu définie (bord gauche/droit ou plafond/sol).
   - **Mort instantanée** : Si le joueur tombe en dehors de l'écran (au-delà du sol), il meurt.

### 6. **Collision avec les plateformes semi-solides**
   - **Passage à travers le bas** : Le joueur peut sauter à travers une plateforme par le bas, mais se pose dessus en descendant.

Ces catégories devraient couvrir l'essentiel des interactions de collision dans un jeu de plateforme 2D sans ennemis ni objets collectables, mais avec des mécanismes d'escalade ou de rebond sur les murs.
