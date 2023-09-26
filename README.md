# Exercice Bootstrap 3 - Maquette Responsive

Intégrez la maquettes en utilisant la grille Bootstrap.

**Commencez par intégrer uniquement la grille**, puis ajoutez le contenu par la suite.

### Trouver les maquettes

Le fichier se trouve:

- dans l'équipe de votre classe
- dans le projet _FD-03-Bootstrap_

Il se nomme _03 - Bootstrap - Maquette responsive_.

Vous pouvez également le trouver [ici](https://www.figma.com/file/ob6AbllnkmcjYp5zIB0nPQ/03---Bootstrap---Maquette-responsive?type=design&mode=design&t=pIX4MsevseT457JG-1).

### Rendre les colonnes visibles

Afin de rendre les colonnes visibles, vous pouvez utiliser la CSS suivante:

```CSS
.row + .row {
  margin-top: 16px;
}

.row > .col,
.row > [class^=col-] {
  padding-top: 12px;
  padding-bottom: 12px;
  background-color: rgba(86, 61, 124, .15);
  border: 1px solid rgba(86, 61, 124, .2);
}
```

![](_screenshots/maquette1@1x.png)
