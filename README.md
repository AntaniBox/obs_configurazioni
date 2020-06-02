# Backup delle configurazioni per OBS
Repository contenente i "backup" o meglio i file utilizzati dalla AntaniBox per le registrazioni.

Per il ripristino e/o ricreare l'ambiente di registrazione seguire le istruzioni.
Backup delle configurazioni per OBS

## Riconoscimenti e attribuzioni
Il NO-LOGO "42" è di [Martinultima](https://en.wikipedia.org/wiki/User:Martinultima) e rilasciato su [Wikimedia Commons](https://commons.wikimedia.org/) con licenza [Creative Commons BY-SA](https://creativecommons.org/licenses/by-sa/3.0/deed.en)

## Ripristino

Esempio di ripristino Progetto42:
1. Entrare nella cartella Progetto42
1. Entrare nell'ultima cartella con nome "Config_{ANNO}_v{Release}"
1. Copiare tutti i file ".png" in una cartella
1. Copiare il contenuto della cartella "obs-studio" dove risiedono le configurazioni di OBS (Generalmente /home/{NOME_UTENTE}/.config/obs-stuidio)
1. Quindi aprire OBS-Studio, è necessario ripristinare i collegamenti con le immagini:
  1. Nelle proprietà della fonte "MascheraVideo"
  1. Nei filtri della fonte "Relatore"
