Three steps to get running: 

1) Download and extract the distribution (SEHBAU_win.zip for windows, SEHBAU_ubu.gzip for ubuntu, _deb for debian, _fed for fedora)

   Strip its suffix from the folder name, ie. rename SEHBAU_win to SEHBAU.

2) Set the rootpath variable 'rootSehBau' in script globalsSB:

   Python: AdminPy/globalsSB.py. Or run script setup.py in directory SEHBAU: it will set the variable automatically.

   Matlab: AdminMb/globalsSB.m  
   
3) Run the demo scripts in the main folder SEHBAU
   
   Python: exsbAll.py: requires modules numpy, matplotlib, skimage
       
   Matlab: exsbAll.m. If nothing is happening, then perhaps start Matlab in a shell with 'matlab -nodesktop' (it could be a problem with DLLs).
   

For more info see the documentation link under DokuSBlink.pdf
