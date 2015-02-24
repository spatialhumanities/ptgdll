# ptgdll
DLL-Bibliothek für das Cyclone Point Cloud Format PTG 1.0

Projektmappe ptg.sln in Visual Studio 2008 (oder höher) öffnen.

Folgende Befehlsargumente für das Testprogramm PTG-DLL_test01 unter [Eigenschaften][Debuggen][Befehlsargumente] zum Testen eingeben:

>>>HolzturmSpitze-0.ptg   h.pts<<<

Diese Version ist um eine Funktion zur Umrechnung vom Scanner- ins globale Koordinatensystem erweitert.

Sowie um eine Lesefunktion mit wahlfreiem Zugriff: 

PTG__GetPointColRow(ptg_handle,column,row,&point)

Weitere Programme sind:

   ptx2ptg.exe : Konvertierung vom PTX-Format nach PTG

   ptgview.exe : Kleiner 3D-Viewer für eine PTG-Datei (aus LAS-tools)


19.04.2011
Fredie Kern
