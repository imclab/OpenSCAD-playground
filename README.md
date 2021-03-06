What's all this then?
=======================

These are just a few things I've made with [OpenSCAD](http://www.openscad.org/) and [SolidPython](https://github.com/SolidCode/SolidPython).



Try it yourself
=======================


1. Install [OpenSCAD](http://www.openscad.org/) (available for Linux, Mac OS X, and Windows).

2. Clone this repository and run the demo program.

        git clone git://github.com/yosinski/OpenSCAD-playground.git
        cd OpenSCAD-playground
        python tree.py

3. Open the produced ```tree.scad``` file in OpenSCAD. Export as [STL](http://en.wikipedia.org/wiki/STL_%28file_format%29) and 3D print if desired.

That's all you need to get started!

Tweak the parameters in ```tree.py``` to make other L-system designs, try out ```windPendant.py```, or come up with something completely new.



Tree
=======================

The file ```tree.py``` generates random arboreal specimens like the one below. The code implements a stochastic [L-system](http://en.wikipedia.org/wiki/L-system), seeded randomly or with a number of the user's choice &mdash; in this case 918.

### Results of ```python tree.py 918``` rendered in OpenSCAD

[![tree_render](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_500.png)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918.png)

### After 3D printing

[![tree_printed](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_printed_500.jpg)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_printed.jpg)

### Soaking in NaOH to soften the support material for removal

[![tree_soaking](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_soaking_500.jpg)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_soaking.jpg)

### All cleaned up. Note that several of the fragile smaller branches broke during cleaning.

[![tree_cleaned](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_cleaned_500.jpg)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsTree918/tree_918_cleaned.jpg)



Wind Pendant
=======================

The file ```windPendant.py``` generates a top that, when spun, relies on [persistance of vision](http://en.wikipedia.org/wiki/Persistence_of_vision) to produce an image.

### Results of ```python windPendant.py``` rendered in OpenSCAD

[![windPendant1](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendant1_500.png)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendant1.png)

[![windPendant2](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendant2_500.png)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendant2.png)

### After 3D printing

[![windPendantPrinted](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendantPrinted_500.jpg)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendantPrinted.jpg)

### Spinning

[![windPendantSpinning](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendantSpinning_500.jpg)](https://github.com/yosinski/OpenSCAD-playground/raw/master/resultsWindPendant/windPendantSpinning.jpg)



Acknowledgements and License
=======================

The ```pyopenscad.py``` and ```sp_utils.py``` files are copied from [SolidPython](https://github.com/SolidCode/SolidPython) and are included in this distribution, for convenience, under their original [GNU LGPL](http://www.gnu.org/licenses/lgpl.txt) license. All other code is released under [GNU GPL v3](http://www.gnu.org/licenses/gpl.txt).




![-](http://s.yosinski.com/1px_OpenSCAD-playground.png)
