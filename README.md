#Normalized Spectral Clustering Implementation
# Building And Running
In order to run the project you need to build the C - Python extension:
In terminal run the following:
python3 setup.py build_ext --inplace
# Compilation
In terminal run the following:
bash comp.sh
# Testing
In terminal run the following:
bash tester.sh testfiles <interface> <regular> <leaks> <efficiency>
Syntax for the above command:
1. interface - c / py / both - The interface you want to test.
2. regular - yes/no -  Run or not the regular tests.
3. leaks - yes/no - Run or not memory leak tests.
4. efficiency - yes/no - Run or not efficiency tests.

   Running Example:
   bash tester.sh testerfiles both yes yes no
   


