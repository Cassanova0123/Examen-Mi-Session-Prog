# Examen-Mi-Session-Prog
Turbo Rival
Mais qu'est ce que Turbo Rival?
Turbo Rivals est un jeu de course dynamique où les joueurs affrontent des adversaires contrôlés par l'intelligence artificielle (IA) sur différents circuits. Les courses sont enrichies par un système d'objets spéciaux qui peuvent être utilisés stratégiquement pendant la course.
Ce répositoire contient la hiérarchie de classe et le code pour le projet Turbo Rival basé sur Unity3d et C#

Hiérachie de classe:

Véhicule(Classe A):
Attributs:
- Vitesse
- Position
- Direction
Méthodes:
- Accélération()
- Ralentissement()
- Tounrer()
- Bosst()
  Classe Player(Hérite de la classe A)
  Atrributs:
  -Score
  Méthodes:
  -Interface()
  IA(Hérite de la classe A)
  Attributs:
  - Niveau de difficulté
  Méthodes:
  - RoadCalcuation()
  - Éviter les obstcales()
    Classe Objet
    Attributs:
  - Durée
  - Type
Méthodes:
  - AppliquerEffet(véhicule)
MissileGuide (Hérite de ObjetSpécial)
Attributs :
Cible
Méthodes :
AppliquerEffet(véhicule)
TacheHuile (Hérite de ObjetSpécial)

Méthodes :
AppliquerEffet(véhicule)
EMP (Hérite de ObjetSpécial)

Méthodes :
AppliquerEffet(véhicule)
Circuit

Attributs :
ListeVéhicules (max 10)
Scoreboard
Obstacles
Méthodes :
AjouterVéhicule(véhicule)
SupprimerVéhicule(véhicule)
MettreAJourScore()
  
  
  


