# SparRec: An effective matrix completion framework of missing data imputation for GWAS

## Demo Bundle

### Obtaining and Running the Demo

#### Requirement: MATLAB

1.  A copy of MATLAB and the statistics toolkit is needed to run this software.
2.  [Download](http://www.mathworks.com/products/matlab/) MATLAB and install it if needed.

#### Requirement: Demo files and test database.

1.  You need to download the demo code bundle `code_demo.tar.gz` and extract it.
    -   The demo code archive includes two folders: "LRMC\_s" and "MBI\_BCU" which in turn contain the MATLAB code and data required to demonstrate the algorithms presented in the paper. More information and instructions for running each demo is given in the "README.txt" files contained in each folder.

#### Running the MBI/BCU Demo on Linux/Windows (MATLAB GUI)

1.  Before running the MATLAB GUI you need to unpack `code\_demo.tar.gz` (using an untar application such as [7-Zip](http://www.7-zip.org/)).
2.  Then simply open the "MBI_BCU" subfolder in the MATLAB GUI and type the following to run the demo:

```
    run_demo
```

#### Running the MBI/BCU Demo on Linux (console)

1.  Unpack the Demo:

        tar -xvf code_demo.tar.gz

2.  Change to the "MBI_BCU" sub folder of the "code_demo" top-level folder:

        cd code_demo/MBI_BCU

3.  No configuration should be needed; you can just run the demo with the following command:

```
    matlab -nodisplay -nosplash -r run_demo 
```

#### Running the LRMC-s Demo

1.  The LRMC-s demo code and data are located in the "LRMC\_s" subfolder.
2.  Running the demo is similar to running the MBI/BCU code demo. The demo file you need to execute in MATLAB is in the "demo" subfolder, and is named `Demo\_FPCA\_vs\_Mendel.m`.

### Contact Us

Questions, suggestions, comments, etc? Send email to `jcausey@astate.edu`.

