<table>
    <tr>
        <th style="background-color: #ffcccc;">Nom de l'article</th>
        <th style="background-color: #ccffcc;">Modèle utilisé</th>
        <th style="background-color: #ccccff;">Corpus de données</th>
        <th style="background-color: #ffcc99;">Task/methode</th>
        <th style="background-color: #99ccff;">Spécificité</th>
        <th style="background-color: #ffccff;">Question de recherche</th>
    </tr>
    <tr>
        <td>The VoiceMOS Challenge 2023: Zero-Shot Subjective Speech Quality Prediction for Multiple Domains</td>
        <td>Divers modèles soumis par les participants : CNN, Transformer, Wav2Vec 2.0, XLSR, HuBERT, etc.</td>
        <td>eval BC2023 (french TTS), TMHINT-QI (speech enhanced), SVCC2023 <br>train SOMOS; BVCC; BC past years; VCC 2018</td>
        <td>1. TTS French <br>2. Singing Voice conversion <br>3. Speech enhanced & Noisy</td>
        <td>Pas de label pour les corpus en évaluation. Se concentre sur le zero-shot</td>
        <td>Comment améliorer les performances des modèles de prédiction MOS "zero-shot" pour la qualité vocale sur divers corpus de test non vus pendant l'entraînement ?</td>
    </tr>
    <tr>
        <td>LE-SSL-MOS: Self-Supervised Learning MOS Prediction with Listener Enhancement</td>
        <td>Modèle LE-SSL, basé sur Wav2Vec 2.0 et un module d'amélioration d'auditeur</td>
        <td>Train Corpus VC, VCC2022 <br>eval BC2023 (french TTS), TMHINT-QI (speech enhanced), SVCC2023</td>
        <td>Utilise Wav2Vec 2.0 avec une phase d'apprentissage auto-supervisé, suivie d'un vecteur listener concaténé avec celui de Wav2V2</td>
        <td>Pas de label pour les corpus en évaluation.</td>
        <td>Comment les caractéristiques spécifiques de l'auditeur (comme la sensibilité ou les préférences auditives) peuvent-elles être incorporées pour améliorer la prédiction de la qualité vocale auto-supervisée ?</td>
    </tr>
    <tr>
        <td>SQAT-LD: SPeech Quality Assessment Transformer Utilizing Listener Dependent Modeling for Zero-Shot Out-of-Domain MOS Prediction</td>
        <td>Transformer avec modélisation dépendante de l'auditeur + input spectrogramme</td>
        <td>train VCC2022, BVCC <br>eval BC2023 (french TTS), TMHINT-QI (speech enhanced), SVCC2023</td>
        <td>Utilise un transformer</td>
        <td>Document inaccessible</td>
        <td>Comment la modélisation basée sur les auditeurs peut-elle être exploitée pour améliorer la prédiction de la qualité vocale en mode "zero-shot", particulièrement sur des données hors du domaine d'entraînement ?</td>
    </tr>
</table>
