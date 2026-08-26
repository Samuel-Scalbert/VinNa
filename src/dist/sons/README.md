Sons pour la section #bar.

⚠️ IMPORTANT : garde une extension qui correspond au vrai format du fichier.
Un enregistrement iPhone (Voix Memos) exporte en .m4a — s'il est renommé en
.wav sans le convertir, le navigateur ne sait pas le décoder et le son ne
joue pas (ou joue de façon aléatoire selon le navigateur). Si tu ajoutes un
nouvel enregistrement, garde l'extension d'origine (.m4a, .mp3, .wav, peu
importe) et mets à jour le chemin correspondant dans `SOUND_FILES` (dans
index.html) s'il diffère.

Fichiers actuels :

- demarrage.wav  → joué au lancement de la roue (~1.5s, un "vroum" qui monte).
  Actuellement absent : retombe automatiquement sur un son synthétisé tant
  que ce fichier n'existe pas.
- victoire1.m4a à victoire5.m4a
    → joués quand la roue s'arrête (un est tiré au hasard à chaque fois).
      Ajoute/retire des fichiers dans le tableau `tada` de `SOUND_FILES`
      (dans index.html) pour changer le tirage — n'importe quel nombre de
      fichiers fonctionne.

Si un fichier est manquant ou illisible, le site retombe automatiquement
sur un son synthétisé (aucun risque de silence).
