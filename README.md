# SPATIAL-CFIS

That is an implementation of SPATIAL-CFIS

To run this code

1, Create "All_Data" folder where the you hold whole dataset

2, Create "Data" folder include two folders "Testing" and "Training Data" and in folder Training Data create two folders "gray" and "hod".

3, Create "Img", "Rel", "Result", "U", "V" folders

Run following command

pip install -r requirement.txt

python3 main.py --sessid [add session ID] --config [path to config file] --data [path to data folder] --output [path to output image folder] --[path to accuracy folder]

*Note all above folder put in same workspace with your code and we use python 3 version 3.6.x
