# Progetto di Tirocinio - Università di Trento

## Ricostruzione 3D da Dataset Sintetici

Questo progetto di tirocinio è stato sviluppato presso l'Università di Trento e riguarda la **ricostruzione 3D** a partire da dataset sintetici utilizzando due metodi principali:

- **COLMAP**: un software per la ricostruzione 3D che esegue Structure-from-Motion (SfM) e Multi-View Stereo (MVS).
- **SuGaR**: un'alternativa più recente per la ricostruzione 3D basata su 3D Gaussian Splatting.

## Contenuti del Progetto

Il progetto si divide nelle seguenti sezioni principali:

1. **Preparazione del dataset sintetico**: la creazione e gestione dei dataset utilizzati per testare i metodi di ricostruzione 3D.
2. **Implementazione di COLMAP**: l'uso di COLMAP per la generazione di modelli 3D a partire dai dataset.
3. **Implementazione di SUGAR**: ricostruzione tramite SuGaR, per valutare le differenze di prestazioni e qualità rispetto a COLMAP.
4. **Analisi dei risultati**: confronto tra i due metodi in termini di accuratezza e velocità di esecuzione, tramite il software CloudCompare.


## Dataset
Sono stati utilizzati 9 dataset sintetici, ottenuti tramite il [nerf-dataset-creator-plugin](https://github.com/AndreaMas/nerf-dataset-creator-plugin), in particolare 5 outdoor e 4 indoor. Di seguito le informazioni sui dataset.

| Info  | Val |
|-------------------|-----------------|
| **Dimensioni**      |   ~1GB per modello      |
| **Immagini** | 250 per modello |
| **Formato**      | PNG        |
| **Risoluzione**      | 800x800       |


## Risultati

Puoi visualizzare i risultati della ricostruzione 3D ai seguenti link su Google Drive:

https://drive.google.com/drive/folders/1TwfDqCzI4fV9StuTM7iw1mN32opuhV8B?usp=share_link

