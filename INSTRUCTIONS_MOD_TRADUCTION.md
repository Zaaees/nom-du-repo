# 📦 Mod de Traduction "OneWithDeath-French"

## ✅ C'est fait !

J'ai créé un **mod de traduction séparé** qui fonctionne comme un addon au mod principal "One with Death". Ce mod suit les standards RimWorld pour les traductions.

## 📁 Structure créée

```
OneWithDeath-French/
├── About/
│   ├── About.xml                    # Métadonnées du mod de traduction
│   └── PublishedFileId.txt          # ID Steam Workshop (à remplir)
├── Languages/
│   └── French/
│       ├── DefInjected/             # 67 fichiers de traduction
│       │   ├── AbilityDef/
│       │   ├── BackstoryDef/
│       │   ├── HediffDef/
│       │   ├── ResearchProjectDef/
│       │   ├── ThingDef/
│       │   └── ... (30 types de Defs traduits)
│       └── Keyed/                   # (vide pour l'instant)
└── README.md                        # Documentation complète
```

## 🎯 Comment récupérer ce mod sur votre ordinateur

### Option 1 : Copier directement depuis GitHub

```bash
# Depuis votre dépôt Git local
git checkout claude/translate-rimworld-mod-french-01WrshGzThgSXNKQ6rKH9irb
git pull

# Le dossier OneWithDeath-French sera maintenant présent
```

### Option 2 : Copier manuellement

1. Récupérez le dossier `OneWithDeath-French/` depuis GitHub
2. Copiez-le dans votre dossier RimWorld Mods :
   - **Windows** : `C:\Program Files (x86)\Steam\steamapps\common\RimWorld\Mods\`
   - **Mac** : `~/Library/Application Support/Steam/steamapps/common/RimWorld/Mods/`
   - **Linux** : `~/.steam/steam/steamapps/common/RimWorld/Mods/`

## 🎮 Comment utiliser ce mod

### Installation dans RimWorld

1. **Assurez-vous d'avoir le mod original "One with Death" installé**
2. Copiez le dossier `OneWithDeath-French` dans votre dossier Mods de RimWorld
3. Lancez RimWorld
4. Allez dans **Options → Mods**
5. Activez les deux mods dans cet ordre :
   ```
   ☑ One with Death (mod original)
   ☑ One with Death - Traduction Française (ce mod)
   ```
6. Redémarrez RimWorld

### Ordre de chargement des mods

**Très important !** L'ordre doit être :

```
1. Ludeon.RimWorld (Core)
2. brrainz.harmony (Harmony)
3. Ludeon.RimWorld.Biotech
4. Ludeon.RimWorld.Anomaly
5. 6224Y.OneWithDeath (MOD ORIGINAL)
6. 6224Y.OneWithDeath.French (TRADUCTION) ← DOIT être après le mod original
```

## 📊 Contenu traduit

- ✅ **24 projets de recherche** - Tous les arbres technologiques
- ✅ **12 capacités nécromantiques** - Toutes les compétences
- ✅ **67 fichiers de définitions** couvrant :
  - Objets et ressources
  - Bâtiments et structures
  - Rituels (Exuvie, Enduvie, Éclats d'âme)
  - Effets et statuts (18 HediffDef)
  - Pensées et interactions
  - Scénario de départ
  - Backstories
  - Interface utilisateur

## 🔄 Différence entre ce mod et les traductions intégrées

### Mod de traduction séparé (OneWithDeath-French) - ✅ Recommandé
- ✅ Peut être installé/désinstallé indépendamment
- ✅ Fonctionne comme les traductions officielles RimWorld
- ✅ Peut être publié sur Steam Workshop
- ✅ Les joueurs peuvent choisir de l'utiliser ou non
- ✅ Facile à mettre à jour séparément

### Traductions intégrées (1.5/Languages et 1.6/Languages)
- Intégrées directement dans le mod original
- Requiert de modifier le mod principal
- Moins flexible pour les utilisateurs

## 📤 Publication sur Steam Workshop (optionnel)

Si vous voulez publier ce mod de traduction sur le Steam Workshop :

1. Ouvrez RimWorld
2. Allez dans **Options → Mods**
3. Sélectionnez "One with Death - Traduction Française"
4. Cliquez sur **"Upload"**
5. Remplissez les informations :
   - **Titre** : One with Death - Traduction Française
   - **Description** : (voir le README.md)
   - **Visibilité** : Publique
   - **Tags** : Translation, French, 1.5, 1.6

## 🔤 Terminologie utilisée

| English | Français |
|---------|----------|
| Necromancy | Nécromancie |
| Undead | Morts-vivants |
| Shambler | Traînant |
| Necrotic Energy | Énergie nécromantique |
| Soul Shard | Éclat d'âme |
| Servitor | Serviteur |
| Altar | Autel |
| Control | Contrôle |

## 📝 Fichiers créés

Voici ce qui a été ajouté au dépôt :

```
✅ OneWithDeath-French/About/About.xml
✅ OneWithDeath-French/About/PublishedFileId.txt
✅ OneWithDeath-French/Languages/French/DefInjected/ (67 fichiers XML)
✅ OneWithDeath-French/README.md
✅ INSTRUCTIONS_MOD_TRADUCTION.md (ce fichier)
```

Plus les traductions intégrées dans le mod original :
```
✅ 1.5/Languages/French/DefInjected/ (67 fichiers)
✅ 1.6/Languages/French/DefInjected/ (67 fichiers)
✅ About/About.xml (modifié avec description française)
```

## ❓ Questions fréquentes

### Q : Quelle version utiliser ?
**R :** Utilisez le **mod de traduction séparé** (`OneWithDeath-French/`). C'est plus propre et plus facile à gérer.

### Q : Puis-je utiliser les deux en même temps ?
**R :** Non, choisissez soit le mod séparé, soit les traductions intégrées. Le mod séparé est recommandé.

### Q : Comment mettre à jour la traduction ?
**R :** Avec le mod séparé, il suffit de mettre à jour le dossier `OneWithDeath-French`. Avec les traductions intégrées, il faut mettre à jour tout le mod.

### Q : Le mod fonctionne-t-il sans Steam ?
**R :** Oui ! Il suffit de copier le dossier dans votre répertoire Mods local.

---

**Branche GitHub** : `claude/translate-rimworld-mod-french-01WrshGzThgSXNKQ6rKH9irb`

**Pull Request** : https://github.com/Zaaees/nom-du-repo/pull/new/claude/translate-rimworld-mod-french-01WrshGzThgSXNKQ6rKH9irb

Bon jeu et longue vie à vos nécromanciens ! 💀🇫🇷
