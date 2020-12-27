 Écrire une ligne de commande qui affiche la sortie d’un cat /etc/passwd, en
retirant les commentaires, une ligne sur deux en partant de la seconde en inversant
chaque login et en triant par ordre alphabétique inversé, en ne conservant que les
logins compris entre FT_LINE1 et FT_LINE2 inclus, séparés par des ", " (sans
les guillemets), et terminés par un ".".

**Exemple** : Entre les lignes 2 et 8, le résultat sera quelque chose du genre :

```ps
$> ./passwd.sh
vamalc_, tsafbrk_, toorsmvc_, toor, tocevod_, tessaelibom_, svc_.
$>
```

> :warning: Respectez strictement l’ordre de l’énoncé.
