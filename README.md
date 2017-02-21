# House_prices_task

##Requirements:
1. Jupyter Notebook  
   The version of the notebook server is 4.3.1 and is running on:  
   Python 2.7.13 |Anaconda 4.3.0 (64-bit) for Windows.
2. Libraries  
   numpy (v>= 1.6.1), pandas (v 0.19.2), matplotlib (v 2.0.0), seaborn (v 0.7.1), sklearn (v 0.18.1).  
   Another versions are not tested, but sklearn 0.18.1 must be.

##Instruction for setup all requirements:
1. Download [Continuum Anaconda for Windows](https://www.continuum.io/downloads) (free version, approx. 400MB), python 2.7, 64 bits.
2. Install it using the default settings for a single user.
3. Open Anaconda Prompt.   
   * For updating sklearn enter and run:   
   ```
   conda update scikit-learn   
   ```
   * For installing seaborn enter and run:  
   ```  
   conda install -c anaconda seaborn=0.7.1  
   ```

##Instruction for reproduce the solution:
1. [Get the code](https://github.com/Tina-Golovchenko/House_prices_task.git).  
2. Save it to Anaconda Scripts folder.  
3. Run Jupyter Notebook and choose House_prices_task\HOUSE_PRICES_TASK.ipynb.  
4. For running code choose the menu item "Cell"->"Run All".  
5. For running the model to make predictions it's enough to enter    
   ```
   predictions = best_model.predict(data_test)
   ```  
6. Predictions are saved in file "House_Price_Task.csv" in the project folder.
