# Who-To-Follow

Developed a social network link prediction model using user attributes, implemented in Python with Scikit-learn and PyTorch.

## MLG Competition Details

Competition Site: [http://140.116.52.202:5566/](http://140.116.52.202:5566/)

Username: *student number*  
Password: *Phone + sth*

# Report Outline
* Introduction
* Methodology - describe all details of your features & methods
  - feature extraction
  - Network model
  - Optimization objective
  - Performance evaluation
* Experimental analysis
  - Baseline1: predict all link with `None`
  - Baseline2: common neighbor, jaccard coefficient, preferrential attachment ... etc(`#commons`)
  - Method3: each-10% `#1`, each-10% `#2`
  - Method4: each-quad `#1`, each-quad `#2`
  - Method5: distribution
  - Method6: use features in baseline2, method3 and method4
* Conclusion
  - conclude the strength
  - future work
