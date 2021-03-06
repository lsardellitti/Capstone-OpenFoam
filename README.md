# Capstone-OpenFoam
OpenFoam samples and working code for capstone

## Import Rear Wing Model

To run the rear wing models, you will need to move the RW.stl file into the `constant/trisurface` folder

### Running OpenFOAM models

Running the examples in this repo come in two forms, depending on the folder. Navigate to the 
appropriate folder in your WSL distibution, and run the following. Check the contents of the folder
to determine which commands to run

```
$ ./Allrun
```

or

```
$ ./importGeometry
$ ./moveGeometry
$ ./run{NAME OF SIMULATION}
```

### Cleaning OpenFOAM models

To clean each folder, returning it to its original state, navigate to the folder and
run the following command
```
$ ./Allclean
```
