# Règles de typographie et de style français

Toutes les réponses, synthèses, rapports et générations de texte en français doivent respecter scrupuleusement les règles de l'Imprimerie nationale et de la typographie française :

1. **Minuscule après deux-points (:)** :
   - Ne jamais mettre de majuscule après les deux-points, sauf s'il s'agit d'un nom propre ou du début d'une citation directe complète entre guillemets.
   - Exemple correct : Conclusion : la démonstration est solide. (et non Conclusion : La démonstration...).

2. **Casse des titres (Sentence case)** :
   - Dans les titres, intertitres et sous-titres, seule la première lettre du premier mot prend une majuscule (ainsi que les éventuels noms propres).
   - Bannir formellement le style anglais (« Title Case » avec majuscule à chaque mot).
   - Exemple correct : Analyse personnalisée du devoir (et non Analyse Personnalisée Du Devoir).

3. **Guillemets français** :
   - Utiliser exclusivement les guillemets français en chevrons «  et  » (avec espace à l'intérieur), et non les guillemets anglais droits " ou courbes “ ” dans le corps du texte.

4. **Accents sur les majuscules et capitales** :
   - Les majuscules doivent toujours être accentuées : À, É, È, Ê, Î, Ô, Û, Œ, etc. (« L'accent a pleine valeur orthographique » — Académie française).

5. **Ponctuation double et espacement** :
   - Respecter l'espace avant les signes de ponctuation double (:, ;, ?, !) et l'espace normale après.

6. **Esperluette (&)** :
   - Proscrire l'esperluette & dans le texte rédigé et les titres ; employer toujours la conjonction de coordination « et ».

7. **Numérotation et siècles** :
   - Écrire les siècles en chiffres romains avec exposant : XIXᵉ siècle, XXIᵉ siècle.
   - Utiliser les abréviations ordinales soignées : 1ʳᵉ, 1ᵉʳ, 2ᵈᵉ, 2ᵉ.

---

## Application obligatoire au texte visible de l'interface (UI, HTML, JS)

Ces règles s'appliquent sans exception à **toute modification ou création de texte visible pour l'utilisateur** dans l'application Mentor Concours (fichiers index.html, scripts JavaScript, gabarits, alertes, notifications, etc.) :

1. **Titres, sous-titres, onglets, badges et boutons** :
   - Casse de phrase stricte (*sentence case*) : seule la première lettre prend une majuscule (ex. : Capes externe, Agrégation interne, Méthodologie officielle, Exigences spécifiques).
   - Jamais de majuscules sur les adjectifs ou compléments, sauf noms propres.
   - Jamais d'esperluette & dans les libellés (écrire « et »).

2. **Deux-points dans l'interface** :
   - Toute mention introduite par deux-points (:) prend une minuscule (ex. : Ex. : le réel..., 🏛️ Exigences spécifiques : dissertation hors-programme).

3. **Accents sur les majuscules** :
   - Vérifier scrupuleusement les majuscules en début de libellé ou de question (ex. : À-t-on..., Épreuve..., État...).

4. **Ordinaux et durées** :
   - Écrire 1ʳᵉ, 2ᵈᵉ, 3ᵉ, etc. (et non 1ère, 2ème).
   - Espace insécable avant le symbole d'heure h (ex. : 7 h, 6 h).

---

## Règle impérative d'étalonnage et de formulation des critères d'évaluation

Toute règle d'évaluation, de plafonnement ou de valorisation issue de l'étalonnage empirique (dans `Grilles_Evaluation/GRILLE_DISSERTATION.md`, `Grilles_Evaluation/GRILLE_EXPLICATION_DE_TEXTE.md`, `GCloud/index.js`, `index.html`, `Github/index.html` ou les scripts d'évaluation) doit respecter sans exception les quatre principes suivants :

1. **Universalité méthodologique et conceptuelle stricte** :
   - Les règles doivent toujours être formulées comme des **lois méthodologiques et philosophiques générales** (nature de l'opération conceptuelle, structure de l'aporie, statut de la médiation doctrinale, rigueur de l'exégèse immanente, cohérence des engagements théoriques).

2. **Interdiction formelle de toute référence nominative au corpus d'étalonnage (zéro sur-ajustement / *overfitting*)** :
   - Ne **jamais** citer dans une règle d'évaluation ou un prompt système l'identifiant d'une copie, le nom d'un candidat, l'intitulé d'un sujet particulier ou l'auteur d'un texte du corpus d'étalonnage comme déclencheur de barème (bannir par exemple toute mention du type « Règle Condillac », « Sujet sur le bonheur », « Texte de Spinoza », etc.).

3. **Différenciation explicite par concours et par épreuve** :
   - Chaque règle doit préciser à quelle épreuve et quel format horaire elle s'applique :
     - **Capes externe** : 1ʳᵉ épreuve écrite disciplinaire de dissertation (6 h) ; 2ᵈᵉ épreuve écrite disciplinaire appliquée / explication de texte (6 h).
     - **Agrégation interne** : 1ʳᵉ épreuve de dissertation philosophique (7 h) ; 2ᵈᵉ épreuve d'explication de texte philosophique (6 h 30).
     - **Agrégation externe** : 1ʳᵉ épreuve de composition de philosophie générale sans programme (7 h) ; 2ᵈᵉ épreuve de composition de philosophie sur programme (7 h) ; 3ᵉ épreuve d'histoire de la philosophie sur œuvre au programme (6 h).

4. **Synchronisation systématique** :
   - Toute évolution de l'étalonnage doit être répercutée simultanément dans les grilles de référence (`GRILLE_DISSERTATION.md` et `GRILLE_EXPLICATION_DE_TEXTE.md`), dans le moteur d'évaluation backend (`GCloud/index.js`) et dans l'interface (`index.html` et `Github/index.html`).

5. **Vigilance sur le préfixe historique de certains fichiers du corpus (`Copies/`)** :
   - Ne **jamais** se fier au seul préfixe `Agreg_Int` dans le nom de fichier des 9 copies suivantes de 2020 et 2021 (`PH` et `DM`), qui sont toutes des épreuves officielles de l'**Agrégation externe** (comme l'indiquent leurs sujets sur programme *La représentation*, *Le Sophiste*, *Le commun*, *Pensées sur l'interprétation de la nature* et les compositions hors-programme *Qu'apprenons-nous de nos affects ?* et *Que peut le droit ?*) :
     * `2020_Agreg_Int_Dissert_Representation_7_PH` et `2020_Agreg_Int_Dissert_Representation_11-5_DM` $\rightarrow$ **Agrégation externe** (2ᵈᵉ composition sur programme : *La représentation*).
     * `2020_Agreg_Int_Dissert_HorsProg_8_PH` et `2020_Agreg_Int_Dissert_HorsProg_10_DM` $\rightarrow$ **Agrégation externe** (1ʳᵉ composition hors-programme : *Qu'apprenons-nous de nos affects ?*).
     * `2020_Agreg_Int_Explic_Platon_4-5_PH` et `2020_Agreg_Int_Explic_Platon_12_DM` $\rightarrow$ **Agrégation externe** (3ᵉ épreuve sur programme : Platon, *Le Sophiste*).
     * `2021_Agreg_Int_Dissert_Commun_8-5_PH` $\rightarrow$ **Agrégation externe** (2ᵈᵉ composition sur programme : *Le commun*).
     * `2021_Agreg_Int_Dissert_Droit_8_PH` $\rightarrow$ **Agrégation externe** (1ʳᵉ composition hors-programme : *Que peut le droit ?*).
     * `2021_Agreg_Int_Explic_Diderot_7_PH` $\rightarrow$ **Agrégation externe** (3ᵉ épreuve sur programme : Diderot).

---

## Protocole impératif de modification et de versionnage du moteur d'évaluation

Il est formellement interdit de modifier le code d'évaluation (`GCloud/index.js`, grilles de référence, prompts système) ou de déployer une nouvelle version sans respecter scrupuleusement les deux règles suivantes :

1. **Validation explicite préalable de l'utilisateur** :
   - Ne jamais modifier le code d'évaluation ni déployer sur Cloud Run sans avoir d'abord soumis la proposition détaillée (diagnostic, diff exact, impact prévisible) à la validation explicite de l'utilisateur et reçu son accord formel.
   - Une question ou un constat d'écart de notation posé par l'utilisateur appelle d'abord une explication et un diagnostic partagé, jamais une modification unilatérale immédiate du moteur en production.

2. **Sauvegarde systématique et versionnage incrémental** :
   - Tout changement validé doit faire l'objet d'un archivage préalable du code sous un nouveau numéro de version dans `Backups_Versions/` (ex. : `v3_3_...`), contenant les fichiers modifiés et les logs de benchmark correspondants.
   - Mettre à jour systématiquement `Backups_Versions/JOURNAL_ETAPES_ET_RETOUR_ARRIERE.md` pour garantir la possibilité d'un retour en arrière immédiat en un clic.

---

## Protocole impératif d'actualisation transparente et gestion anti-cache du frontend

Pour garantir que les candidats et utilisateurs bénéficient immédiatement, sans délai et de manière 100 % transparente de toute amélioration, correctif ou évolution sans jamais avoir à vider manuellement leur cache navigateur (ni faire Ctrl+F5) :

1. **Sanctuarisation absolue du script anti-cache** :
   - Le bloc de détection et d'actualisation transparente (`checkAppUpdate`, écouteurs d'événements `visibilitychange`, `window.focus`, et surveillance périodique en arrière-plan) situé au sommet du script principal dans `index.html` et `Github/index.html` est sanctuarisé.
   - Il est formellement interdit de le supprimer, de le désactiver, de le commenter ou d'altérer sa séquence de synchronisation préalable avant rechargement.

2. **Incrémentation systématique de `APP_BUILD_VERSION` à chaque modification** :
   - À **chaque modification ou mise à jour ultérieure** de l'interface, du style, de la méthodologie ou de la logique frontend (`index.html` et `Github/index.html`), la constante `APP_BUILD_VERSION` doit impérativement être incrémentée sous le format standard : `YYYY.MM.DD.<libelle_explicite>_vX_Y`.
   - C'est ce changement de valeur qui déclenche l'actualisation automatique et transparente chez tous les utilisateurs connectés.

3. **Sauvegarde de sécurité avant rechargement** :
   - Toute actualisation automatique déclenchée par une nouvelle version doit d'abord sauvegarder le texte en cours de rédaction (`saveCurrentDraftToLastRenderedSubject`), persister le stockage local (`persistStorageData`) et purger la synchronisation Cloud (`flushCloudSyncNow`) avant d'exécuter `window.location.replace`.
   - Ne jamais interrompre une évaluation IA en cours de traitement : si une analyse est en cours de calcul, le rechargement doit être différé automatiquement pour laisser l'évaluation se terminer et afficher le rapport.

4. **Synchronisation binaire obligatoire (`fc.exe /b`) et déploiement** :
   - Avant tout commit et push, s'assurer que `index.html` et `Github/index.html` sont strictement identiques bit-à-bit via `fc.exe /b "index.html" "Github\index.html"`.
   - Pousser systématiquement sur la branche `main` du dépôt GitHub pour alimenter le site en ligne sur GitHub Pages.


