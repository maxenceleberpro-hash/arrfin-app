---
title: Arrfin · Assistance
---

# Arrfin

Arrfin est un lecteur pour **ton propre** serveur [Jellyfin](https://jellyfin.org), sur iPhone et Apple TV. Il n'inclut aucun contenu : il lit ce qui est sur ton serveur.

## Assistance

Une question, un problème, une idée ? Écris à **[maxenceleber.pro@gmail.com](mailto:maxenceleber.pro@gmail.com)**, en précisant ton appareil (iPhone ou Apple TV) et la version d'Arrfin (Réglages › À propos).

### Questions fréquentes

**Arrfin ne trouve pas mon serveur.**
Saisis l'adresse que tu utilises dans un navigateur, par exemple `192.168.1.20:8096`. L'iPhone ou l'Apple TV doit être sur le même réseau que le serveur, ou le serveur doit être joignable depuis Internet. Autorise aussi Arrfin dans Réglages › Confidentialité › Réseau local.

**Le QR code de l'Apple TV ne fonctionne pas.**
L'iPhone et l'Apple TV doivent être sur le même Wi-Fi, et Arrfin doit être installé et connecté sur l'iPhone. Pour une connexion sans mot de passe, active Quick Connect dans Jellyfin (Tableau de bord › Général).

**Où trouver une clé TMDB ?**
Crée un compte gratuit sur [themoviedb.org](https://www.themoviedb.org), puis Paramètres › API. Colle la « clé d'API » dans Arrfin.

**Où trouver la clé de Radarr ou Sonarr ?**
Dans chacun : Settings › General › API Key.

**Les sous-titres sont décalés.**
Le fichier de sous-titres a sans doute été fait pour une autre version du film. Dans la lecture, ouvre Audio et sous-titres › Synchronisation :
- si l'écart grandit au fil du film, choisis la vitesse « Fichier 23,976 → vidéo 25 i/s » (Arrfin le fait seul quand c'est certain) ;
- si l'écart est constant, avance ou recule les sous-titres par pas de 0,5 s ou 5 s.

Le réglage est mémorisé pour ce film. Pour éviter le problème à la source : dans Jellyfin, Tableau de bord › Bibliothèques › Sous-titres, coche « Ne télécharger que les sous-titres parfaitement adaptés ».

**J'ai acheté Arrfin+ mais il est verrouillé.**
Réglages › Arrfin+ › Restaurer mes achats, avec le même compte Apple que pour l'achat. Un achat débloque l'iPhone et l'Apple TV.

**Comment fonctionne l'essai gratuit ?**
7 jours, une fois par compte Apple. Rien n'est facturé à la fin : Arrfin+ se verrouille simplement si tu ne l'achètes pas.

## Confidentialité

Arrfin ne collecte aucune donnée. [Lire la politique de confidentialité](confidentialite.html).

---

*Arrfin utilise l'API TMDB mais n'est ni approuvé ni certifié par TMDB. Jellyfin est un projet libre indépendant d'Arrfin.*
