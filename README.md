# SESexact
A program for the exact computation and triangulation of solvent-excluded surface i.e. molecular surface.

For installation in linux (ubuntu 20.04):

(I): DOWNLOAD "sesxV001.tar.gz"
In USER's home directory:
(1) CREATE a directory called "softBio" (~/sofrBio)
(2) MOVE "sesxV001.tar.gz" to ~/softBio
(2) tar -xzvf sesxV001.tar.gz. It will create a directory "sesx"

(II) MODIFY .bashrc file by ADDing

LD_LIBRARY_PATH=$HOME/softBio/sesx/lib:$LD_LIBRARY_PATH
export LD_LIBRARY_PATH

(III):
   (1) GO TO ~/softBio/sesx/bin
   (2) run ./sesx

