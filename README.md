# mpAdminV2
![image](https://github.com/MaitrePoisson1/Script/assets/134843685/f24993e2-ce3b-4c7e-8721-071137d9205d)

Un menu admin 100% configurable !

### Avant le premier lancement
* Etape 1 : Aller dans "shared\client_config.lua" et "shared\server_config.lua" puis de la ligne 3 à 10, modifier le trigger de déclaration par rapport à votre framework.
* Etape 2 : Aller dans "shared\client_config.lua" puis de la ligne 91 à 137, modifier les grades par rapport à ceux de votre serveur et faite pareille dans "shared\server_config.lua" de la ligne 11 à 18.
* Etape 3 : Aller dans "shared\server_config.lua" puis de la ligne 111 à 115, modifier les types d'argent par rapport à ceux de votre serveur.
* Etape 4 : Aller dans "shared\client_config.lua" puis de la ligne 300 à 338, modifier les commandes par rapport à celle de votre serveur.
* Etape 5 : Aller dans "shared\client_config.lua" puis à la ligne 215, modifier en true si vous utilisez un système d'arme en item.

### Configurer la bannière du menu
* Etape 1 : Aller dans "stream\commonmenu.ytd" puis modifier la bannière "interaction_bgd" ou sinon remplacer le fichier et metter bien le nom de votre bannière à la ligne 17 dans "shared\client_config.lua".

### Configurer les permissions du menu
* Etape 1 : Aller dans "shared\server_config.lua" puis de la ligne 139 à 211, le chiffre après l'option signifie que tout les grades à partir de lui jusqu'au plus haut on accès à l'option.

### Configurer les logs du menu
* Etape 1 : Aller dans "shared\server_config.lua" puis de la ligne 20 à 109, modifier le webhooks par rapport à ceux de votre discord puis modifier de la ligne 117 à 120 les informations des logs.
