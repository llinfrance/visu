# Visu


Visu is an user interface library based on pyqtgraph to open and process data image .

It can open .spe .SPE, .sif and .TIFF files

It can make plot profile and data measurements  analysis

    https://github.com/julienGautier77/visu

## Requirements
*   python 3.x
*   Numpy
*   PyQt5
*   pyqtgraph (https://github.com/pyqtgraph/pyqtgraph.git) 
    * pip intall pyqtgraph
*   qdarkstyle (https://github.com/ColinDuquesnoy/QDarkStyleSheet.git)
    * pip install qdarkstyle
*  sifread.py
    *   https://github.com/lightingghost/sifreader/tree/master/sifreader
*  winspec.py 
    *   https://github.com/antonl/pyWinSpec
    
## Installation
*   from PyPi
    *   pip install visu

## Usage


    from PyQt5.QtWidgets import QApplication
    import sys
    import qdarkstyle
    import visu

    appli = QApplication(sys.argv)   
    appli.setStyleSheet(qdarkstyle.load_stylesheet_pyqt5())
    e = visu.visual.SEE()
    e.show()
    appli.exec_() 

-----------------------------------------
-----------------------------------------
