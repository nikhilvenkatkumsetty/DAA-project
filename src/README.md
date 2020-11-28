
Instructions to run the Makefile :

To run all programs at once, please make sure that you are in the \src sub folder, and run the following commands in the terminal:


->  make clean

->  make install

->  make edmonds

->  make drake-hougardy


The first command uninstalls the networkx library, if already present in the system. This is because our project runs on a modified version of the networkx library
called the dorthrithil-networkx library.


The second command installs the dorthrithil-networkx and the numpy libraries (if they don't exist in your system)


The third command runs the Edmonds' Blossom Alogrithm 


The fourth command runs the Drake - Hougardy Approximation Alogrithm



Instructions to run each file :

1) To run the Edmonds' Algorithm, please enter the command - python3 blossom.py

2) To run the Drake - Hougardy Algorithm, please enter the command - python3 Drake_Hougardy_Matching.py
