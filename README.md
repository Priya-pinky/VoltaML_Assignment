# VoltaML_Assignment

Here in this assignment the dataset contains a modified version of https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000 which only contains the classes nv, bkl, mel( around 550 images each).

# **DATA**
1) nv - Melanocytic nevi are benign melanocyte neoplasms that can take many different forms, all of which are covered in our series. From a dermatoscopic perspective, the variants can be very different.

2) bkl - Seborrheic keratoses, also known as "senile warts," solar lentigo, which is a flat variant of seborrheic keratosis, and lichen-planus-like keratoses (LPLK), which is a seborrheic keratosis or a solar lentigo with inflammation and regression, are all included in the general category of "benign keratosis." The three categories may appear to be distinct under the microscope, but we put them together because biologically they are comparable and frequently described histopathologically under the same general phrase. Since lichen planus-like keratoses can exhibit morphologic characteristics that mimic melanoma and are frequently biopsied or removed for diagnostic purposes, they pose particular challenges from a dermatoscopic perspective.

3) mel - Melanoma, a malignant tumour formed from melanocytes, can take various forms. A straightforward surgical excision can cure it if caught early enough. Melanomas   can be invasive or non-invasive (in situ). We included all melanoma subtypes, including melanoma in situ, however we did not include non-pigmented, subungual, ocular,   or mucosal melanoma.


# **MODEL**
We used transfer learning to many models and ultimately decided on the Final Model based on the data we gathered during the training.

# ** PROCESS**
1) Data Processing
     Preprocess the data so that it is properly encoded and clean.
   
 2)**EXPERIMENT**
     Writing a training loop with checkpoint system and utility methods for managing checkpoints and saved files.Trying out different configurations of the models given      above and selecting the best model and configuration.
     
 3) **Grad-CAM**
     Implementing inference method with built in Grad-CAM.
   
