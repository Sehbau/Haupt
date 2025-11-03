Three steps to get running: 

1) Download and extract the distribution (SEHBAU_win.zip for windows, SEHBAU_ubu.gzip for ubuntu, _deb for debian, _fed for fedora)

   Strip its suffix from the folder name, ie. rename SEHBAU_win to SEHBAU.

2) Set the rootpath variable 'rootSehBau' in script globalsSB:
   
   Matlab: AdminMb/globalsSB.m  
   
   Python: AdminPy/globalsSB.py

3) Run the demo scripts in the main folder SEHBAU

   Matlab: exsbAll.m. If nothing is happening, then perhaps start Matlab in a shell with 'matlab -nodesktop'. It could be a problem with DLLs.
   
   Python: exsbAll.py, ie. python -i exsbAll.py. 
            If your python executable is called 'python3' (or something else), you need to change that in script exsbAll.py too. 

For more info see the documentation DokuSB.pdf (in this repository, or in the downloaded distribution)
