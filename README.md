# sesX
A program for the exact (analytic) computation and exact triangulation of solvent-excluded surface i.e. molecular surface. Here "exact" triangulation means that each of the three vertices of any surface triangle is computed analytically. 

For installation in linux (ubuntu 20.04):

(I): DOWNLOAD "sesxV002_linux.tar.gz" (Releases/tags on the right)

In USER's home directory:

(1) CREATE a directory called "softBio" (~/softBio) 

(2) MOVE "sesxV002_linux.tar.gz" to ~/softBio

(2) tar -xzvf sesxV002_linux.tar.gz. It will create a directory "sesx"

(II) MODIFY .bashrc file by ADDing

LD_LIBRARY_PATH=$HOME/softBio/sesx/lib:$LD_LIBRARY_PATH

export LD_LIBRARY_PATH

(III):

   (1) GO TO ~/softBio/sesx/bin
   
   (2) RUN ./sesx  or ./sesx PDBfile

For installation in Windows 10
   DOWNLOAD "sesxV002_windows.zip", UNZIP it, GO TO directory sesFinal and FOLLOW the instructions in README.txt

For Usage please see "sesx_instruction.pdf"

The vidoes that associated with the intstruction are 
https://www.youtube.com/watch?v=GPd5xR69P-c&t=7s
https://www.youtube.com/watch?v=vgVB_JylSqI&t=1s
or seach "shaozi wang" in youtube

# sesA
   A program for the analytic computations of solvent-accessible surface area and solvent-excluded surface area.
   
   "sesa_linux.pdf" and "sesa_windows.pdf" are, respectively, the linux and windows instructions for usage and output. 
   
   "sesaV001.tar.gz" has the linux files including the binary
   
   "sesaV001_windows.zip" has the windows files including the binary

   The same set of files could also be downloaded directly from the "sesA" repository. 
   
