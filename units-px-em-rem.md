# Dans la conception de sites web, `rem`, `px` et `em` sont des unités de mesure utilisées pour les propriétés CSS, en particulier pour la taille des polices et l'espacement

- `px (pixels)`: Il s'agit d'une unité fixe. Si vous fixez la largeur d'un élément à 100px, il aura toujours une largeur de 100 pixels, quels que soient les paramètres de l'utilisateur ou la taille de l'écran. C'est précis, mais non évolutif.

- `em`: Cette unité est relative à la taille de la police de l'élément parent. Si vous fixez la taille de la police d'un élément à 2em, elle sera deux fois plus grande que la taille de la police de l'élément parent. Par exemple, si la taille de la police de l'élément parent est de 16 px, 2em équivaudra à 32 px. Ceci est utile pour créer des designs réactifs.

- `rem` (root em):  Similaire à `em`, mais relative à la taille de la police racine (html). Elle offre une taille plus cohérente car elle ne dépend pas de la taille de l'élément parent. Si la taille de la police racine est de ``16px`` et que vous fixez la taille d'un élément à ``2rem``, elle sera de ``32px`` 🎉

## Exemples

```
body {
    font-size: 16px; /* root font size */
}

h1 {
    font-size: 2rem; /* 2 * 16px = 32px */
}

p {
    font-size: 1.5em; /* if parent font size is 20px, then 1.5em = 30px */
}

footer {
    font-size: 14px; /* parent size for example */
}

footer p {
    font-size: 1em; /* 1 * 14px = 14px because this is relative to footer */
}
```