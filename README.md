Un semplice programma in fortran che ho pubblicato per il mio video su Youtube.

Se stai utilizzando Linux Debian, installa Fortran:
```plaintext
sudo apt-get install gfortran
```
Apri il terminale di linux.
Crea un nuovo file sorgente Fortran utilizzando un editor di testo come nano:
```plaintext
nano somma_numeri.f90
```
Incolla il codice Fortran fornito in questo repository nel tuo file appena creato.
Premi Ctrl + O per salvare il file e Enter per confermare il nome del file.
Premi Ctrl + X per uscire dall'editor nano.

Compila il programma utilizzando il compilatore gfortran:
```plaintext
gfortran -o somma_numeri somma_numeri.f90
```
Esegui il programma compilato in questo modo:
```plaintext
./somma_numeri
```
