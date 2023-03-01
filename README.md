Conformément à l'adresse email utilisée pour générer la clé GPG, il faut :
git config --local user.email "denis@peyrusaubes.com"
il a aussi fallu que je procède à la manipulation suivante pour qu'au moment de l'ajout de la clé publique dans github, il trouve bien l'adresse mail à utiliser :
https://docs.github.com/en/authentication/managing-commit-signature-verification/associating-an-email-with-your-gpg-key



git config --local --list
