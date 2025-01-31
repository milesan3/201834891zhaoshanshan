Clustering
===========
project description
--------------------
* Compare eight clustering algorithms from NMI and runtime.

DataSet
-------------
* The data of Tweets after process.

Requirements
-------------
* python==3.5
* scikit-learn==0.20.0

File introduction
----------------
* Utils:
  + Tweets.txt: datasets,containing 'text' and 'cluster'
  + Process_Tweets.txt: texts
  + Initial_Label.txt: clusters/labels
  + TfIdf_Vec.txt: weight matrix
  + weight.pkl: weight matrix(The format is pkl)
  + label.pkl: clusters/labels(The format is pkl)
  + utils.py:  
    Extract text and labels from the original data.  
    calculate the weight matrix according to TFIDF.  
    save the weight matrix and labels as pkl files for subsequent use.  

* Initial:
  + Initial_Main.py: Use sklearn to implement eight clustering algorithms.
  + Initial_NMI_Result.txt: The NMI of eight clustering algorithms.

* Modify:
  + Modify_Main.py:  
    Improve each clustering function in Initial_Main.py.    
    calculate NMI and run_time for comparison.    
  + Modify_NMI_Result.txt: The NMI and run_time of eight clustering algorithms.  

Result
======
* Modify_NMI_Result.txt


