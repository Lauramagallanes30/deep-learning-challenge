# deep-learning-challenge
Please let me know if you have trouble accessing any of the files and I will get that fixed right away. I did use Xpert Learning Assistant and ChatGPT to check my work and assist with errors that I didn't understand I also asked for assistance from my instructor throughout class on portions I did not understand. Please let me know if you have questions.
Thank you! Laura Magallanes

Analysis

Overview of the Analysis 
- The aim of this analysis was to create a deep learning model that accurately predicts the success of organizations applying for funding using AlphabetSoup. The model is intended to classify whether an organization will be either successful and unsuccessful. The coding process included preparing the data, scaling numerical data, training a neural network and added other features to omtpimize efficiency.

Results

- Target Variable: IS_SUCCESSFUL (binary: 1 = successful, 0 = unsuccessful).
- Features: (APPLICATION_TYPE, AFFILIATION, CLASSIFICATION,USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL, etc.)
- Removed: (EIN, NAME).

Model Architecture:
- Input Layer: Same as the number of features in the dataset.
- First Hidden Layer: 64 neurons with ReLU activation (2,048 parameters).
- Second Hidden Layer: 32 neurons with ReLU activation (2,080 parameters).
- Output Layer: 1 neuron with Sigmoid activation (33 parameters).

- Total Parameters: 4,161 (16.25 KB)
- Trainable Parameters: 4,161
- Non-Trainable Parameters: 0

Model Performance:
- Training Accuracy: 72.03%
- Loss: 0.579

Conclusion:
The model reached 72.03% accuracy, slightly below the target percentage. Further adjustments are needed to meet the desired 75% goal such as refining the model layering, increasing the number of epochs, or adjusting the neurons. But, overall, the model is efficient and will assist in the process of determining the success of organizations applying for funding. 

