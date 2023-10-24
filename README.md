#### All documents are defined according to the following meanings respectively:

##### dataprocess_seg.ipynb:  
Pre-processing of the raw data before the segmentation to obtain Train_img folder, Test_img folder, Mask_LV folder and Mask_noLV folder.

##### segmentaion.ipynb:  
Segmentation the LV part for the test set. We obtain the result Test_Mask_LV(input_mask) folder which are saved into Test_Mask_LV folder after the operation of a thresold segmentation.

##### dataprocess_train.ipynb:  
Pre-processing of the train data before the classification. We calculatemedical metrics, and save them into DataTrain.csv.(Before calculating the medical metrics, we obtain Mask_RV folder, Mask_Myocardium folder firstly)

##### dataprocess_test.ipynb:  
Pre-processing of the test data before the classification. We calculate the medical metrics,and save them into Test(inputmask).csv. (Before calculating the medical metrics, we obtain Test_Mask_RV folder, Test_Mask_Myocardium folder firstly)

##### classification.ipynb:  
Train the model of classification and predicate the catagory of the patients in the test set. The results are saved into prediction.csv.
