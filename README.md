# MSE Exposure Time Calculator (ETC)
## S. Pak Group of Kyung Hee University (KHU)
### Contributors: Soojong Pak, Tae-Geun Ji, Changgon Kim, Hojae Ann, Minkyung Yang, Taeeun Kim, Jennifer Sobeck
### Relevant Publications/Talks:

MSE ETC code generated by the KHU Group

### Dependencies 
The recommended set-up for the user's Python environment and package dependencies are listed below.  If desired, tt should be easily possible for users to create a separate conda environment with the python/package specifications below.    

python==3.7.9	+	(Minimum python version)  

Necessary Packages:

Tcl/Tk==8.6	+	(python tkinter version check command: python -m tkinter)  
numpy==1.19.5	+ 
scipy==1.6.1 +		 
astropy==4.2.1 + 	  
matplotlib==3.3.3 +  

Ancillary Packages:
*These have likely been installed simulataneously with the install of the "necessary" packages.  The information below allows users to verify the installed package versions.

pyerfa==1.7.3		(mandatory dependency for astropy; exception: v1.7.1 is acceptable)  
cycler==0.10.0		(mandatory dependency for matplotlib)  
kiwisolver==1.3.1	(mandatory dependency for matplotlib)  
Pillow==8.2.0		(mandatory dependency for matplotlib)  
pyparsing=2.4.7		(mandatory dependency for matplotlib)  
python-dateutil==2.8.1	(mandatory dependency for matplotlib)  
six==1.15.0		(mandatory dependency for matplotlib)  

### Download/Installation
In the directory of the user's choice, download the ETC Github repository (if necessary, unzip the contents of the gzip file). 

The code should function immediately after download (and unpacking)

### Operation
If necessary, activate the appropriate conda environment.  Then, type the following at the command line of the user's terminal interface:

`python main.py`

After hitting enter, a GUI interface to the ETC should pop up.  Please enter all necessary values into the GUI interface. 

For the calculations of `S/N` and `Exp. Time`, output data will appear on the termainal screen. 

For the calculations of `S/N v. Magnitude` and `S/N v. Wavelength`, the associated output plot data will appear in a separate display screen (associated withe matplotlib API).

### Termination
In the GUI interface, select/click on the red X button in the upper left-hand corner.





