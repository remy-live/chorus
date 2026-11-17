# Déplacement : Chorus DT + fiche de frais CFDT

Outil web (une seule page, `index.html`) pour les déplacements sur convocation :

- **Convocation** : on dépose le PDF. L'outil lit la date, l'heure, l'objet, le lieu et l'imputation (le NOTA). Le corps des convocations est souvent une image : il est alors lu par reconnaissance de texte, **dans le navigateur**.
- **Distance** : il propose plusieurs itinéraires (IGN le plus court ou le plus rapide, OpenStreetMap).
- **Fiche de frais CFDT Picardie Éducation** : il la remplit en PDF.
- **Chorus DT** : le favori « Remplir mon OM » crée un OM vierge et remplit Général, Prestations, Étapes et Indemnités kilométriques. Il s'arrête avant « Enregistrer ».

## Utilisation

1. Ouvrir https://remy-live.github.io/chorus/ et glisser le bouton **Remplir mon OM** dans la barre de favoris (une seule fois).
2. Dans Chorus DT, cliquer sur le favori : l'outil s'ouvre dans une fenêtre à côté. Il récupère le nom et l'établissement depuis Chorus.
3. Déposer la convocation, vérifier les champs en orange, compléter ceux en rouge.
4. Cliquer sur **Remplir dans Chorus**, puis vérifier dans Chorus, joindre la convocation, **Enregistrer** et **Refuser / Valider**.

⚠️ Dans Chorus, « Générer étapes » enregistre le brouillon. Rien n'est jamais validé par l'outil.

## Données personnelles

- Le PDF de la convocation est lu sur l'ordinateur et n'est envoyé nulle part.
- Le nom, les horaires et l'établissement restent dans le navigateur (stockage local). Ils ne sont transmis qu'à la page Chorus ouverte, par message direct entre les deux fenêtres.
- Seules des **adresses** partent vers des services publics : la Géoplateforme de l'IGN (recherche d'adresses et itinéraires), l'annuaire de l'Éducation nationale (établissements) et le serveur OpenStreetMap (itinéraires).

Auteur : Rémy DEVODDERE.
