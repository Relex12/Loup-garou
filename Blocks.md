# Blocks

| Variables       | Temps                      | Sélection                    | Action           | Déroulement |      |
| --------------- | -------------------------- | ---------------------------- | ---------------- | ---- | ---- |
| camps           | durant (nuit, matin)       | désigne N joueur pour action | donner un statut | vient de mourir |      |
| origine | nuit (1ere, chaque)        | vote N joueur pour action    | tuer (par Rôle)  | possède_pouvoir |      |
| ordre           | avant révélation d'un rôle |                              | connaître carte  | peut_voter |      |
| nb_possible     | après révélation d'un rôle |                              | échanger carte   | peut_parler |      |
|  | pendant le vote            |                              | ressusciter |      |      |
|       | avant le vote              |                              | voir dialogue    |      |      |
|  | | | | | |

> saucisse

Dans le tableau ci-dessous :

* les connexions peuvent être `no`, `left` ou `top+bottom` (ou exclusif)
* les entrées peuvent être  `no` ou `statement`, `input` et `dummy` accompagnés de la liste des noms des entrées

| Nom             | Description                  | Connexion | Entrées                                         |
| --------------- | ---------------------------- | --------- | ----------------------------------------------- |
| Définition rôle | permet de définir le rôle    | no        | statement, input (camp, extension, nb_possible) |
| Camp            | décrit le camp du rôle       | left      | dummy                                           |
| Nombre possible | combien de cartes min et max | left      | dummy                                           |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |
|                 |                              |           |                                                 |



* [éditeur en ligne Blockly](https://blockly-demo.appspot.com/static/demos/blockfactory/index.html)
