<div align="center">
  <a href="https://adeptusrepublica.fr">
    <img src="https://arma3.com/assets/img/wallpapers/artofwardlc/2/thumb.jpg" alt="logoBanner" width=512px/>
  </a>
</div>

# Adeptus Auxiliaire Mod - Arma 3

> [!IMPORTANT]
> Ce projet est en cours d'ouverture à la communauté dans un esprit de partage, d'apprentissage et de collaboration. Il contient des éléments originaux développés par l’équipe Adeptus.  
> Toute inclusion ou référence à une propriété intellectuelle tierce est strictement non-commerciale et sera retirée à la demande des ayants droit.

## 📁 Structure des addons

```plaintext
a3-aux-adeptus/
├─ .hemtt/                    # Fichiers de configuration pour Hemtt
├─ .vscode/                   # Fichiers de configuration pour Visual Studio Code
├─ addons/                    # Dossier principal des addons
│  ├─ cba_settings/             # Addon     | ar_cba_settings         | Fichier de configuration de CBA (Community Base Addons) / inA3PATH = cba_settings_userconfig\
│  ├─ characters/               # Addon     | ar_characters
│  ├─ characters_backpacks/     # Sub-addon | ar_characters_backpacks | Configurations des sacs à dos
│  ├─ characters_helmets/       # Sub-addon | ar_characters_helmets   | Configurations des casques
│  ├─ characters_nvgs/          # Sub-addon | ar_characters_nvgs      | Configurations des accessoires (NVGs)
│  ├─ characters_uniforms/      # Sub-addon | ar_characters_uniforms  | Configurations des uniformes
│  ├─ characters_units/         # Sub-addon | ar_characters_units     | Configurations des unités et groupes
│  ├─ characters_vests/         # Sub-addon | ar_characters_vests     | Configurations des vestes
│  ├─ compositions/             # Addon     | ar_compositions         | Compositions 3den
│  ├─ dialogs/                  # Addon     | ar_dialogs
│  ├─ dialogs_*/                # Sub-addon | ar_dialogs_*            | Configurations de dialogues spécifiques (e.g. main menu, etc.)
│  ├─ inidbi/                   # Addon     | ar_inidbi               | Configuration de inidbi
│  ├─ main/                     # Addon     | ar_main                 | Fichiers principaux du mod
│  ├─ migration/                # Addon     | ar_migration            | Scripts de migration (To be removed in the future)
│  ├─ misc/                     # Addon     | ar_misc
│  ├─ misc_*/                   # Sub-addon | ar_misc_*               | Autres configurations
│  ├─ missions/                 # Addon     | ar_missions             | Scripts et configurations des missions
│  ├─ objects/                  # Addon     | ar_objects
│  ├─ objects_*/                # Sub-addon | ar_objects_*            | Configurations d'objet spécifiques (e.g. paths, supply crates, etc.)
│  ├─ objects_editor/           # Sub-addon | ar_objects_editor       | Configurations des objets pour l'éditeur (useful for mission makers)
│  ├─ objects_misc/             # Sub-addon | ar_objects_misc         | Configurations des objets divers (e.g. bench, etc.)
│  ├─ vehicles/                 # Addon     | ar_vehicles
│  ├─ vehicles_*/               # Sub-addon | ar_vehicles_*           | Configurations de véhicules spécifiques (e.g. bison, laat/i, etc.)
│  ├─ weapons/                  # Addon     | ar_weapons
│  ├─ weapons_*/                # Sub-addon | ar_weapons_*            | Configurations d'armes spécifiques (e.g. rifles, launchers, etc.)
│  ├─ zeus/                     # Addon     | ar_zeus
│  └─ zeus_*/                   # Sub-addon | ar_zeus_*               | Configurations de modules 3den et Zeus (e.g. laat/i drop, garage, etc.)
├─ include/                   # Fichiers nécessaires pour le mod (e.g. CBA)
├─ logo_ca.paa                # Logo du mod
├─ meta.cpp                   # Fichier de métadonnées du mod
├─ mod.cpp                    # Fichier de configuration du mod
└─ README.md                  # Vous êtes ici !
```

## 💻 Coding Guidelines

Pour garantir la qualité et la cohérence du code, veuillez suivre les [coding guidelines](https://ace3.acemod.org/wiki/development/coding-guidelines) d’ACE3 lors du développement de ce mod.

- Utilisez une indentation cohérente.
- Commentez votre code de manière claire et concise.
- Respectez la structure des fichiers et des dossiers.
- Privilégiez la lisibilité et la maintenabilité du code.

## 🤝 Contributeurs

<div align="center">
  <a href="https://github.com/Admors/adeptusAuxiliaire/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=Adeptus-TEAM/a3-aux-adeptus"/>
  </a>
  <br/><br/>
  <p>Nous remercions tous nos Visual Editors et Techniciens pour leur travail sur ce mod.</p>
</div>

## 📜 Licence

<a href="https://www.bohemia.net/community/licenses/arma-public-license-share-alike">
  <img src="https://www.bohemia.net/assets/img/licenses/APL-SA.png" alt="licence">
</a>

Le code source et les ressources **originales** de ce projet sont disponibles sous licence [APL-SA](https://www.bohemia.net/community/licenses/arma-public-license-share-alike).  
Veuillez noter que **les éléments inspirés de franchises existantes ne sont pas couverts par cette licence**.
<br/>

> [!CAUTION]
> This mod is an unofficial resource and is not affiliated with Lucasfilm Ltd, the Walt Disney Company, Electronic Arts Inc., or Twentieth Century Fox. The "Star Wars" brand and all intellectual content in this mod are based on the property of The Walt Disney Company.
>
> Star Wars © 1977 Twentieth Century Fox Film Corporation. All rights reserved. ™ & Copyright 1977 Lucasfilm Ltd. Star Wars logo and all related characters, names, and indicia are trademarks & copyright 2012 Lucasfilm Ltd. All rights reserved, or their respective trademark and copyright holders.
