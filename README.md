Un semplice programma in fortran che ho pubblicato per il mio video su Youtube:
https://youtu.be/Vr209n8IDoM

Se stai utilizzando Linux Debian, installa Fortran:
```plaintext
sudo apt-get install gfortran
```
Effettua il download del file fortran
```plaintext
wget https://raw.githubusercontent.com/anthonyborriello/fortrancalculator/main/somma_numeri
```
Compila il programma utilizzando il compilatore gfortran:
```plaintext
gfortran -o somma_numeri somma_numeri.f90
```
Esegui il programma compilato in questo modo:
```plaintext
./somma_numeri
```
