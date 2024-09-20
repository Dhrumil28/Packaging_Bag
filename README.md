# Packaging_Bag
This file contains the program for allen bradley PLC in which program of conveyer bag filling is embedded.

Process is as follows: - 

1) Bags are placed for grippers to pickup

2) Bag is selected to print lot no , serial no and the month (10 sec).
   
3) Bag placed under hopper to fill up, it will take about 20 sec for 50 Kg and 30 sec for 80 Kg, operator can select the lot using HMI.

4) Bag is then sealed up using the sewing machine (5 Sec).

5) It is further moved up to conveyer belt for (10 sec).

6) The cartesian gantry robot will pick up the bag and place it in pallet (3 sec).

7) Total 12 bags are needed to complete the pallet
