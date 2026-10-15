<p align="center">
  <img src="https://raw.githubusercontent.com/florentinH/folio-releases/main/icon.png" width="96" alt="">
</p>

<h1 align="center">Folio</h1>

<p align="center">
  Éditeur de PDF simple, gratuit et 100 % hors ligne.<br>
  Fusionner, découper, réorganiser, annoter, signer… sans jamais envoyer vos documents sur Internet.
</p>

## Télécharger

| Système | Fichier |
| --- | --- |
| **Windows** 10 / 11 | [⬇ Folio-Windows.exe](https://github.com/florentinH/folio-releases/releases/latest/download/Folio-Windows.exe) |
| **macOS** (Intel et Apple Silicon) | [⬇ Folio-Mac.dmg](https://github.com/florentinH/folio-releases/releases/latest/download/Folio-Mac.dmg) |
| **Ubuntu, Debian, Linux Mint** | [⬇ Folio-Linux.deb](https://github.com/florentinH/folio-releases/releases/latest/download/Folio-Linux.deb) |
| **Fedora, openSUSE** | [⬇ Folio-Linux.rpm](https://github.com/florentinH/folio-releases/releases/latest/download/Folio-Linux.rpm) |
| **Autre Linux** | [⬇ Folio-Linux.AppImage](https://github.com/florentinH/folio-releases/releases/latest/download/Folio-Linux.AppImage) |

Ces liens donnent toujours la dernière version. Toutes les versions : [page des versions](https://github.com/florentinH/folio-releases/releases).

## Installer

### Windows

1. Ouvrez `Folio-Windows.exe`.
2. Si Windows affiche « Windows a protégé votre ordinateur », cliquez sur **Informations complémentaires** puis **Exécuter quand même**.
   Ce message apparaît pour les applications qui ne sont pas encore connues de Microsoft.

### macOS

1. Ouvrez `Folio-Mac.dmg` et faites glisser **Folio** dans le dossier **Applications**.
2. Au premier lancement, macOS peut refuser d'ouvrir l'application. Allez dans **Réglages Système → Confidentialité et sécurité**, puis cliquez sur **Ouvrir quand même** en bas de la page.
3. Si macOS indique que l'application « est endommagée », ouvrez le Terminal et tapez :
   ```
   xattr -cr /Applications/Folio.app
   ```

### Linux

- **.deb** : double-cliquez sur le fichier, ou dans un terminal :
  ```
  sudo apt install ./Folio-Linux.deb
  ```
- **.rpm** :
  ```
  sudo dnf install ./Folio-Linux.rpm
  ```
- **.AppImage** : rendez le fichier exécutable puis lancez-le :
  ```
  chmod +x Folio-Linux.AppImage
  ./Folio-Linux.AppImage
  ```

## Mises à jour

Folio vérifie tout seul s'il existe une nouvelle version. Quand c'est le cas, un bouton **Mettre à jour** apparaît en bas à droite de la fenêtre : un clic suffit.

## Vos documents restent chez vous

Tout le travail se fait sur votre ordinateur. Folio n'envoie jamais vos fichiers, ne demande pas de compte et fonctionne sans connexion. Le seul accès à Internet sert à vérifier les mises à jour.
