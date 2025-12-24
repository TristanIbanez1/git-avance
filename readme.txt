Installation du hook pre-commit :

1) Copier le hook dans le dépôt local :
   cp hooks/pre-commit .git/hooks/pre-commit

2) Rendre le hook exécutable :
   chmod +x .git/hooks/pre-commit

Test :
- faire un commit et répondre 'y' pour générer suivi/commitInfo.txt
