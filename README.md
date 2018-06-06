ISTALLAZIONE MANUALE DI OS X SU PENNA USB O DISCO O SD CARD



Usare il comando "createinstallmedia" in Terminale
Dopo aver scaricato il programma di installazione, collega l'unità flash USB o un altro volume che verrà utilizzato come programma di installazione avviabile. Assicurati che disponga di almeno 12 GB di spazio di archiviazione disponibile.
Apri Terminale selezionandolo nella sottocartella Utility della cartella Applicazioni.
Digita o incolla uno dei seguenti comandi in Terminale. In questi esempi si presume che il programma di installazione si trovi ancora nella cartella Applicazioni e che il nome del volume sia MyVolume. Se il volume ha un nome diverso, sostituisci MyVolume di conseguenza.



TERMINALE DI MAC OS X

COPIARE INTERA LINEA UTILE 
PS LA PASSWORD RICHIESTA E' QUELLA AMMINISTRATORE E NON VERRà VISUALIZZATA ALLO SCHERMO 

(TEMPO NECESSARIO TRA I 5 E 65 MINUTI SECONDO VELOCITà DISCO )


High Sierra:
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ macOS\ High\ Sierra.app

Sierra:
sudo /Applications/Install\ macOS\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ macOS\ Sierra.app

El Capitan:
sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app

Yosemite:
sudo /Applications/Install\ OS\ X\ Yosemite.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ OS\ X\ Yosemite.app

Mavericks:
sudo /Applications/Install\ OS\ X\ Mavericks.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ OS\ X\ Mavericks.app
