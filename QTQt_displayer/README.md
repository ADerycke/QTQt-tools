## What is a code ??!! :
The "software" is avaible as an .exe files that you can just start on your computer without any additionnal thinks to do. Regarding to the size of the file (>25 Mo) it's not easy for me to drop it on GitHub, so you need to download it from my... google drive.

Link to the .exe file :
[QTQt_displayer](https://drive.google.com/drive/folders/1_GGJ04T9lJ65IefS4SPoSup3R-byYIhL?usp=sharing)
![image](https://github.com/ADerycke/QTQt-utility/assets/130437433/515af761-44b9-47eb-872c-d141ae0ca30d)

No installation needed, but if you want to have the helps, don't forget to download the "QTQt_Helps" folder and put it in the same folder as the .exe
Note : for a god know reason i'm not able to compile it on MacOS, so it's only available on windows by now... 

## The user interface :
You can have some tips to helps you to understand plots meaning, but only if you downloaded the "QTQt_Helps" folder and put it in the same as the .py.

You can enter/change different parameters depending of what you want to display, or let them by default :

![image](https://github.com/ADerycke/QTQt-tools/assets/130437433/4e1728ff-64be-4f97-9a89-a296802b8235)

You can use this tool bar to edite as you desire each plot of the figure :
![image](https://github.com/ADerycke/QTQt-tools/assets/130437433/26c1cf3a-fdd3-470c-8834-91fb528c0244)

## QTQt displayer (PyQt) : (for beginner in code or people that want an interface)
It's a python code that use a graphical interface (base on Qt) to help users to produce the wanted plot. Personnaly, it's this one that i use.

![image](https://user-images.githubusercontent.com/130437433/232014922-cff7b4bd-494b-4a20-9ea2-1599ed84f15c.png)

## QTQt displayer (multi files) : (for coder)
It's the raw python code (withou the interface above) with the function to retriver the data and plot. if you are interested to do your own plots, it maybe can be usefull to you.
(personnaly i use it as a develpemnt and debug)

## needed python librairy:

*Basic :* 
  - numpy (handle some calculation)
  - pandas (handle most of data table)
  - xarray (handle 3D data table for time-temperature histories)
  - matplotlib for pyplot (handle all the figure generation)
  - pyrolite (contain the geological time scale)

*Needed for the GUI interface :* 
  - Pyside6 for Qt (handle all the user interface)
  - tqdm (usefull to follow things for progress bar)
