# fast-dm-gui
A python-based graphical user interface for Windows users of fast-dm - a diffusion model analysis tool. 

The fast-dm algorithm was originally developed by Voss & Voss (2007):

https://www.ncbi.nlm.nih.gov/pubmed/18183889

The GUI was developed by Stefan Radev and Veronika Lerche as an extension to the new version of fast-dm (Voss, Voss, & Lerche, 2015): 

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4376117/

It provides a flexible interface to the earlier cmd tool written in C including a visualization module and parallelised parameter estimation across participants.

If you want to use this GUI, follow these steps:

1. Download or clone this repository

2. Download and install the latest version of Python 3.x

3. Install the following libraries via the command line using pip:

   pip install pyqt5 qdarkstyle numpy pandas matplotlib
  
4. Start the GUI by double-clicking the main.pyw file or by referencing it via cmd:

   python ../your-path-to-repository/gui/main.pyw
   
Alternatively, you can find a click-through Windows installer at our webpage, plus a general introduction to fast-dm:

http://www.psychologie.uni-heidelberg.de/ae/meth/fast-dm/

Linux/Mac compatibility is coming soon...

A tutorial for the GUI is coming soon...
