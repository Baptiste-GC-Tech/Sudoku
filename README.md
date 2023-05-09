# Sudoku

Le dossier "board" servira à sauvegarder les anciennes progression des tables de Sudoku qui n'auront pas été résolue par le joueur. Une fois résolue, elles seront supprimées.

Le dossier "engine" servira, en MVC, à stocker le code qui accepetra les inputs du joueur, les traiteras, et enverras les requêtes de rafaraichissement visuel à la partie fenêtré. Comme le logiciel est simple, je peut me permettre de mettre le Modèle et le Contrôleur au même endroit

Le dossier "window" servira, en MVC, à stocker le code qui permettra d'afficher graphiquement l'état de la grille de sudoku, et d'accepter des inputs de l'utilisateurs. Ceci seront directement envoyés au Contrôleur.

Le dossier "lib" servivra à strocker toutes les potentiels libraires dont le projet pourrais avoir besoin pour fonctionner (je pense notamment à SDL 2.0)