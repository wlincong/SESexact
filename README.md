# SESx
A program for the exact (analytic) computation and exact triangulation of solvent-excluded surface i.e. molecular surface. Here "exact" triangulation means that each of the three vertices of any surface triangle is computed analytically. 

For installation in linux (ubuntu 20.04):

(I): DOWNLOAD "sesxV002.tar.gz" (Releases/tags on the right)

In USER's home directory:

(1) CREATE a directory called "softBio" (~/sofrBio)

(2) MOVE "sesxV001.tar.gz" to ~/softBio

(2) tar -xzvf sesxV001.tar.gz. It will create a directory "sesx"

(II) MODIFY .bashrc file by ADDing

LD_LIBRARY_PATH=$HOME/softBio/sesx/lib:$LD_LIBRARY_PATH

export LD_LIBRARY_PATH

(III):

   (1) GO TO ~/softBio/sesx/bin
   
   (2) RUN ./sesx  or ./sesx PDBfile

For installation in Windows 10
   DOWNLOAD "sesX_windows.zip", UNZIP it, GO TO directory sesFinal and FOLLOW the instructions in README.txt


