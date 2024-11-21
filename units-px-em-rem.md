![hero image](https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F516n6wvtnrp8fjkr2dzr.png)

# Dans la conception de sites web, `rem`, `px` et `em` sont des unités de mesure utilisées pour les propriétés CSS, en particulier pour la taille des polices et l'espacement

- `px (pixels)`: Il s'agit d'une unité fixe. Si vous fixez la largeur d'un élément à 100px, il aura toujours une largeur de 100 pixels, quels que soient les paramètres de l'utilisateur ou la taille de l'écran. C'est précis, mais non évolutif.

- `em`: Cette unité est relative à la taille de la police de l'élément parent. Si vous fixez la taille de la police d'un élément à 2em, elle sera deux fois plus grande que la taille de la police de l'élément parent. Par exemple, si la taille de la police de l'élément parent est de 16 px, 2em équivaudra à 32 px. Ceci est utile pour créer des designs réactifs.

- `rem` (root em):  Similaire à `em`, mais relative à la taille de la police racine (html). Elle offre une taille plus cohérente car elle ne dépend pas de la taille de l'élément parent. Si la taille de la police racine est de ``16px`` et que vous fixez la taille d'un élément à ``2rem``, elle sera de ``32px`` 🎉

## Exemples

```

```

![some units](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F2v0z3jkdsqzhgi7kfcj5.png)

### Source to translate and continue to develop units

https://dev.to/akramnarejo/how-to-decide-css-units-for-responsive-website-nk4