Instructions on running the program:

1. This code is written in Python3. Download and install Python and pip.

2. Before running the code, you need to install sklearn , GRidSearchCV packages.

3. I have used Jupyter Notebook for this code.

4. Download the train_file and test_file and change the location according to the code.
	
	train_data = pd.read_csv("/Users/rachanathota/CS584/HW2_THOTA/train_data.csv",index_col=0)

	test_data = pd.read_csv("/Users/rachanathota/CS584/HW2_THOTA/test_data.csv",index_col=0)
	
5. Once file location is updated, you are set to run the program. 

6. If the program is finished, you can be able to see 'finished' message and the program will generate a file 'output_XBG.txt' in the same location.

7. After submitting that file in miner, you will be able to see the rank and f1-score.
 