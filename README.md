# Riffwerk-Modelle

Fertig umgewandelte Modelle für Riffwerk, eine Mac-App zum Üben von Songs. Die App lädt sie
beim ersten Gebrauch selbst herunter; hier liegen nur die Dateien, kein App-Code.

## htdemucs_6s (Spurtrennung)

Release [`htdemucs_6s-1`](../../releases/tag/htdemucs_6s-1), Datei `htdemucs_6s.zip` (52 MB, entpackt 74 MB).

- Inhalt: `htdemucs_6s.mlmodelc` (kompiliertes Core-ML-Modell, fp16) und `htdemucs_6s-LICENSE.txt`.
- Herkunft: Modell „htdemucs_6s“ aus [Demucs](https://github.com/facebookresearch/demucs)
  von Alexandre Défossez (Meta AI Research). Die Gewichte sind unverändert, nur nach Core ML
  übertragen; STFT und iSTFT rechnet die App selbst.
- Lizenz: Der **Code** von Demucs steht unter MIT, siehe [LICENSE-demucs](LICENSE-demucs). Die
  **Gewichte** fallen laut Autor nicht unter MIT, sondern sind nur für wissenschaftliche Zwecke
  bereitgestellt ([demucs#327](https://github.com/facebookresearch/demucs/issues/327),
  [demucs#508](https://github.com/facebookresearch/demucs/issues/508)). Riffwerk nutzt sie nur
  übergangsweise in der kostenlosen Beta und ersetzt sie durch ein eigenes, selbst trainiertes Modell.
  Die Datei `htdemucs_6s-LICENSE.txt` im ZIP nennt nur die MIT-Lizenz des Codes.
- SHA-256: `42ce5cee0d9ce7d7e972b9b6e2b64be18732419e5380a76eda350c3fe9e39a01`
