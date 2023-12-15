# TP - Labyrinthe
![image](https://github.com/code-gt/TP-Labyrinthe/assets/120173004/da2eeecf-653f-429c-aef5-a6f942ffbdc8)

**Objectif :** Apprendre à manipuler le DOM avec JavaScript pour générer dynamiquement un labyrinthe interactif.

**Description :**

Dans cette activité, vous allez créer un jeu de labyrinthe où le joueur doit guider un personnage à travers un labyrinthe pour atteindre la sortie. Dans un premier temps, le labyrinthe sera fourni directement dans le HTML. Ensuite, vous utiliserez JavaScript pour générer dynamiquement le labyrinthe.

**Étapes :**

1. **HTML fourni :** Le labyrinthe est représenté à l'aide de divs avec différentes classes. Analysez le HTML et identifiez les classes associées aux murs, au personnage et à la sortie.
2. **Styles CSS :** Les styles CSS associés aux différentes classes sont définis dans le fichier **`style.css`**. Familiarisez-vous avec ces styles et comprenez comment ils affectent l'apparence des cellules du labyrinthe.

****3. Script JavaScript (Génération Dynamique)****

```jsx
// main.js
document.addEventListener('DOMContentLoaded', function() {
    const maze = document.getElementById('maze');

    // Génération dynamique du labyrinthe ici...

    // Reste du code (déplacement du personnage, etc.)
});
```

Cette fois-ci c’est à vous de jouer, vous devrez essayer de déplacer le personnage dans le labyrinthe pour qu’il atteigne la sortie en utilisant du Javascript.

### **Partie 2 : Génération Dynamique du Labyrinthe avec JavaScript**

Maintenant, passons à la partie amusante où vous allez utiliser JavaScript pour générer dynamiquement le labyrinthe. Assurez-vous de travailler dans le fichier **`script.js`**.

1. **Suppression du Labyrinthe Fourni :** Commencez par supprimer le labyrinthe fourni dans le HTML. Vous allez le recréer entièrement avec JavaScript.
2. **Création d'un Tableau de Labyrinthe :** Déclarez une variable qui représentera le tableau du labyrinthe. Utilisez un tableau multidimensionnel où chaque élément représente une cellule du labyrinthe. Vous pouvez utiliser des chiffres ou des chaînes pour représenter différents éléments (par exemple, 0 pour une cellule vide, 1 pour un mur, 2 pour le personnage, 3 pour la sortie).

```jsx
const mazeData = [
    [1, 1, 1, 1, 1],
    [1, 2, 1, 3, 1],
    [1, 1, 1, 1, 1]
    // ... Ajoutez autant de lignes que nécessaire
];
```

1. **Génération du Labyrinthe :** Utilisez JavaScript pour générer dynamiquement le labyrinthe en parcourant le tableau **`mazeData`** et en créant des éléments div pour chaque cellule. Ajoutez ces divs au conteneur du labyrinthe.

```jsx

<p>Indices :</p>

document.getElementById

document.createElement
```

1. **Déplacement du Personnage :** Modifiez la logique de déplacement du personnage pour qu'elle fonctionne avec le labyrinthe généré dynamiquement.

```jsx
<p>Indices :</p>

function moveCharacter(rowOffset, colOffset) {
// Votre code ici

// Vérifiez si le joueur a atteint la sortie
        if (mazeData[characterRow][characterCol] === 3) {
            alert('Félicitations, vous avez atteint la sortie !');
        }
}
```

### **Partie 3 : Améliorations et Défis Bonus (Optionnels)**

Maintenant que vous avez réussi à générer dynamiquement un labyrinthe, n'hésitez pas à explorer les améliorations et défis bonus. Vous pouvez ajouter des fonctionnalités supplémentaires pour rendre le jeu encore plus intéressant !

1. **Améliorations Possibles :**
    - **Génération Aléatoire :** Modifiez le script pour générer un labyrinthe aléatoire.
    - **Plusieurs Niveaux :** Ajoutez la possibilité de passer à différents niveaux de labyrinthes.
    - **Animations :** Intégrez des animations lors du déplacement du personnage.
2. **Défis Bonus :**
    - **Obstacles Dynamiques :** Ajoutez des obstacles qui peuvent changer de position.
    - **Chronomètre :** Intégrez un chronomètre pour mesurer le temps pris pour atteindre la sortie.
    

Et surtout … Amusez vous !
