# projet-apprentissage-par-renforcement---Fronze-Lake-
 Implémentation de Policy Iteration, Value Iteration et Epsilon-Greedy dans un environnement Frozen Lake

Introduction :
L'objectif est d'implémenter et de comparer trois algorithmes fondamentaux en apprentissage par renforcement : Policy Iteration, Value Iteration et l'algorithme Epsilon-Greedy. Ces algorithmes seront appliqués à un environnement Frozen Lake, représenté graphiquement.

Environnement Frozen Lake : Le Frozen Lake est un environnement de grille où un agent (en bas à droite) doit naviguer à travers une surface glacée pour atteindre un objectif (en haut à gauche) tout en évitant des cases dangereuses. La grille est représentée ici graphiquement, et chaque case peut être soit une case gelée (sûr, reward = 0), une case dangereuse (trou, reward = -10), ou l'emplacement de l'objectif (reward = 10). L'agent peut se déplacer vers la gauche, droite, en haut ou en bas. Utiliser le dessin graphique pour définir les valeurs initiales des états et les récompenses associées.

<img width="591" height="653" alt="image" src="https://github.com/user-attachments/assets/6915514a-4537-4988-9198-f8bda1c62d7c" />

