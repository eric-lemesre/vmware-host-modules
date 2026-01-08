# VMware Host Modules / Modules Hôtes VMware

[English](#english) | [Français](#français)

---
[Original Documentation / Documentation Originale](README.orig.md)

<a name="english"></a>
## English

### Overview
This repository contains patched source code for VMware Workstation/Player host modules (`vmmon` and `vmnet`). These patches are necessary to build the modules on newer Linux kernels where the original sources provided by VMware might fail to compile.

### Credits and Sources
This repository aggregates work from several community contributors to support various VMware versions:

*   **Versions 17.6.0, 17.6.1, 17.6.3**: Based on the work by [philipl](https://github.com/philipl/vmware-host-modules).
*   **Version 17.6.4**: Based on the work by [aurelihein](https://github.com/aurelihein/vmware-host-modules)
*   **Installation Script**: The `pack_and_install.sh` script is derived from [64kramsystem](https://github.com/64kramsystem/vmware-host-modules).

### Original Documentation
The original documentation text has been moved to `REDME.orig.md`.

### Installation
To build and install the modules:

1.  Ensure you have `make`, `gcc`, and kernel headers installed for your current kernel.
2.  Run the provided script:
    ```bash
    chmod +x pack_and_install.sh
    ./pack_and_install.sh
    ```

---

<a name="français"></a>
## Français

### Aperçu
Ce dépôt contient le code source corrigé pour les modules hôtes VMware Workstation/Player (`vmmon` et `vmnet`). Ces correctifs sont nécessaires pour compiler les modules sur des noyaux Linux récents où les sources originales fournies par VMware peuvent échouer à la compilation.

### Crédits et Sources
Ce projet regroupe les contributions de plusieurs dépôts pour supporter différentes versions de VMware :

*   **Versions 17.6.0, 17.6.1, 17.6.3** : Basé sur le travail de [philipl](https://github.com/philipl/vmware-host-modules).
*   **Version 17.6.4** : Basé sur le travail de [aurelihein](https://github.com/aurelihein/vmware-host-modules).
*   **Script d'installation** : Le fichier `pack_and_install.sh` provient de l'utilisateur [64kramsystem](https://github.com/64kramsystem/vmware-host-modules).

### Documentation Originale
Le texte de la documentation originale a été déplacé vers le fichier `REDME.orig.md`.

### Installation
Pour compiler et installer les modules :

1.  Assurez-vous d'avoir `make`, `gcc` et les en-têtes du noyau (kernel headers) installés pour votre noyau actuel.
2.  Exécutez le script fourni :
    ```bash
    chmod +x pack_and_install.sh
    ./pack_and_install.sh
    ```