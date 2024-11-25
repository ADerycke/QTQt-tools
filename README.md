# ! WARNING # 
I move the support of those tools to my website : [deryckehub](https://deryckehub.ovh/en/thermochronology)

# QTQt utilities

This GitHub regroupe several tools that i developed to improve my personnal day-by-day use of [QTQt sofware](https://www.thermonet.universite-paris-saclay.fr/?page_id=294&lang=en) made by [K. Gallagher](https://geosciences.univ-rennes.fr/en/interlocutors/kerry-gallagher) [(Gallagher, 2012)](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2011JB008825).
If you are interested into use it, feel free to try and improve it !

Usefull informations :
  - i work on Windows 10 OS
  - i use VBA and python

**Conceptor : Alexis Derycke** 
  - [Reseach Gate](https://www.researchgate.net/profile/Alexis-Derycke)
  
## Generate He file using Excel table :
Find [one excel file](https://github.com/ADerycke/QTQt-tools/tree/main/Generate%20He%20files%20using%20Excel%20table) that produce helium data files (.txt) for QTQt from a basic table. Note that it allow to review existing data files and add AFT data (already prepare).

![image](https://user-images.githubusercontent.com/130437433/231545265-1091cc0f-4e49-4be5-9c16-937fb3ab0dd6.png)

## Get the modelling "resutls" using Excel :
Find [another excel file](https://github.com/ADerycke/QTQt-tools/tree/main/Get%20the%20modelling%20%22resutls%22%20using%20Excel) that automatically retrieve modelling results (pred. ages, pred LFT...) in two clicks from the "Summary.txt" generate by QTQt.

 ![image](https://github.com/ADerycke/QTQt-utility/assets/130437433/d9b04fdf-b5b9-439e-bfc1-9dcdb9f3f36b)

## QTQt displayer :
Find [a tool](https://github.com/ADerycke/QTQt-tools/tree/main/QTQt_displayer) that produce simple and integrative figure using QTQt results.

![McCLure (Gerin-Guent) - Simple_2](https://github.com/ADerycke/QTQt-tools/assets/130437433/c97758e6-23f7-47f2-b258-bc6c5d836475)
*GUI interface :*
![image](https://github.com/ADerycke/QTQt-tools/assets/130437433/bcca83bc-b131-41f1-b4d2-989bb2cdb8a4)

This tools is avalaible as a an .exe file (only compile on Windows, sorry user) or 2 python code (available through Jupyter NoteBook and partially annoted with french and english comment...). 
Both code done the same thinks : use the "Summary.txt" generate by QTQt after a run to generate a simple and intergrative figure that summarize the data inverions result :

Link to the .exe file :
[QTQt_displayer](https://drive.google.com/drive/folders/1_GGJ04T9lJ65IefS4SPoSup3R-byYIhL?usp=sharing)
![image](https://github.com/ADerycke/QTQt-utility/assets/130437433/515af761-44b9-47eb-872c-d141ae0ca30d)

No installation needed, but if you want to have the helps, don't forget to download the "QTQt_Helps" folder and put it in the same folder as the .exe

Note : for a god know reason i'm not able to compile it on MacOS, so it's only available on windows by now... 

*how it work ?*

  - what is a code ??? : i provide an .exe file that you can use just by cliking on it (windows user only by now)
  - intermediate code user : use the code named "PyQt", is based on a graphical interface (Qt) so you don't need any specific knowledge to run it, except installing the needed library
  - advanced code user : use the code named "multi file" that is a full python and completely cutomisable code

*how can you help ?*

  - if you are a pro coder, don't hesitate to correct/improve those code
  - if you are a pro Qt, please don't juge me and help me to properly do an interface
  - if you are working on MacOS, the code properly work on it but i'm not able to generate a bundle/application that work. So if you can do it don't hesitate to contact me !

*limitation ?*

By now i don't work with Ar/Ar or 4/3He analyses, so it's not gonna show properly results of a this kind of data.
