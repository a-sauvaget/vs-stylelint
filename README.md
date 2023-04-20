# Règles pour Stylelint

Règles définies selon [le standard actuel](https://github.com/stylelint/stylelint-config-standard).

## Configuration de Visual Studio Code

Définition globale des règles, pour tous les projets tant qu'il n'y a pas d'installation se Stylelint pour un projet en particulier.
Dans les paramètres, rajouter :

```json
"stylelint.enable": true,
"css.validate": false,
"scss.validate": false,
"less.validate": false,
"stylelint.configFile": "/path/to/.stylelintrc.json",
"stylelint.stylelintPath": "/path/to/node_modules/stylelint"
```
