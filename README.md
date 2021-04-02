# Source Code of Paper: "A Multi-View SVM Approach for Seizure Detection from Single Channel EEG signals"
The Repository contains source code of accepted paper: "A Multi-View SVM Approach for Seizure Detection from Single Channel EEG signals" IETE Journal of Research, DOI: https://doi.org/10.1080/03772063.2021.1913074. This Article will be online soon.


Read Me
                Multi-view SVM for seizure detection


* Run the code in Google Colab.
* Download the Dataset from weblink mentioned, it automatically creates a folder in the drive of the dataset.
* Run the necessary libraries cell in code.
* Decide the test case, as clearly mentioned in the comments.
* Depending on the test case decide what lines to comment and not to.
For case A vs E :
Comment code lines which contain data2 , X2 ,Y2 . Rest uncommented
For case B vs E :
Comment code lines which contain data2 , X2 ,Y2 . Rest uncommented
For case C vs E :
Comment code lines which contain data1 , X1 ,Y1 . Rest uncommented
For case D vs E :
Comment code lines which contain data1 , X1 ,Y1 . Rest uncommented
For case AB vs E :
Comment code lines which contain data2 , X2 ,Y2 . Rest uncommented
For case CD vs E :
Comment code lines which contain data1 , X1 ,Y1 . Rest uncommented
For case ABCD vs E :
A special cell for this case is given in the code.
Comment code lines which contain data1 , X1 ,Y1 . Rest uncommented
( A line can be commented using the symbol ‘#’ at the start of line)


* The first step is to prepare the data and clean using filters. Run the cells related to this.
* Run all predefined functions necessary for multi-view SVM.
* Next, run the cell in which we have defined the multi-view SVM model.
* Now train the model using stratified K-fold cross-validation.
* For checking the obtained results run the results cell in the last, it will display the results.
* Run the further cells for comparing the multi-view SVM model with single view SVMs.
