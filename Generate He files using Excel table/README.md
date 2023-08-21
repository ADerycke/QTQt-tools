##  How to use this files :
You simply have to download the file, allow the execution of macro and it's ready ! Normally files should work on both windows and mac os.

## basic use :
Click on the "Create Data files" button to generate the QTQt files, a window gonna open to select the destination and files will be name after samples name.

Click on the "Review Data files" button to input data from QTQt files to the excel table.

![image](https://user-images.githubusercontent.com/130437433/234915678-d476d33b-8be8-41be-8122-23c8d0a68e96.png)

## Data structuration :
*how it work :*
  - one line = one crystal
  - same crystal name = same sample
  
![image](https://user-images.githubusercontent.com/130437433/234914900-fd9a55c6-2106-4275-ab05-007f6e760b2b.png)
 
*direct option :*
  - you can input U, Th and Sm or only eU
  - you can add a Rs resample by adding the wanted range in dark-green column
  - you can add an eU resample
  
![image](https://user-images.githubusercontent.com/130437433/234915274-5ff96340-e414-4d75-8824-d198e9e9a0c8.png)
  
*undirect option (when you start the files creation) :*
  - you can add crystal zonation parameters
  - you can generate associated files for Rampe Heating option in case of forward modelling

Example, see the screenshot below :

![image](https://user-images.githubusercontent.com/130437433/234916302-a714cd2a-3d25-4081-92fd-113feea9df99.png)

## various details about QTQt formalisme
Look at the sheet "Info" to get all details about the QTQt files generated 

![image](https://user-images.githubusercontent.com/130437433/233411454-236edd00-b13a-440e-8249-17f5ed8dfad3.png)

## Fission Tracks data

This files is not able generate AFT or AFLT data, but if your already have a QTQt files and you "Review" it and it gona add the ALFT data to the "AFT" sheet.

Then when you gonna create the AHe files, if names are the same for helium and fission tracks data, the FT data gonna be automatically added to produced files.

![image](https://user-images.githubusercontent.com/130437433/234917709-983db875-66a6-41f6-8548-567be16b5766.png)
