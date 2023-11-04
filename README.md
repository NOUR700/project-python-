# project-python-
" Système de Sécurité et de Gestion des Utilisateurs"

Description:
Ce programme puissant qui combine la sécurité, le cryptographie, et la gestion d'utilisateurs pour vous offrir une expérience unique. C'est exactement ce que notre système de gestion des utilisateurs en Python peut réaliser. Enregistrer, authentifier, hacher, chiffrer et signer - tout en un seul endroit pour répondre à vos besoins de sécurité et de gestion des données.

Enregistrement (1):
Lorsque vous vous inscrivez pour la première fois, le programme vous demande de fournir un e-mail valide et un mot de passe sécurisé. Le mot de passe doit contenir au moins une majuscule, une lettre minuscule, un chiffre, un caractère spécial, et être d'une longueur minimale de 8 caractères. Vos informations d'authentification sont ensuite enregistrées dans un fichier nommé "Enregistrement.txt".

Authentification (2):
Lorsque vous revenez, le programme vérifie vos identifiants par rapport au fichier d'enregistrement. Si vos informations existent, vous accédez à un menu d'options de sécurité.

Menu d'Options:
Avec succès, le menu s'ouvre, vous offrant un éventail d'opérations de sécurité et de gestion des données :

A. Hachage (1):
a. Hacher un mot de passe en utilisant l'algorithme SHA256.
b. Hacher un mot de passe en utilisant l'algorithme bcrypt avec génération de sel.
c. Attaquer un mot de passe haché par dictionnaire (pour tester la sécurité du mot de passe).
d. Revenir au menu principal.

B. Chiffrement (RSA) (2):
a. Générer une paire de clés RSA et les enregistrer dans un fichier.
b. Chiffrer un message de votre choix avec la clé publique RSA.
c. Déchiffrer le message chiffré avec la clé privée RSA.
d. Signer un message de votre choix avec la clé privée RSA.
e. Vérifier la signature du message signé.
f. Revenir au menu principal.

C. Certificat (RSA) (3):
a. Générer une paire de clés RSA pour un certificat et les enregistrer dans un fichier.
b. Générer un certificat auto-signé avec la clé privée RSA.
c. Chiffrer un message de votre choix avec ce certificat.
d. Revenir au menu principal.


