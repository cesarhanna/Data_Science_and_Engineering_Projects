This project aims to create couple of models that predict the eye condition based on Optical Coherence Tomography (OCT) image(s). The conditions, or labels that exist in the dataset are as defined as follows:

- AMD (Age-related Macular Degeneration): A common eye condition that causes damage to the macula (central part of the retina), leading to blurred central vision. It's often associated with aging and comes in two forms: dry and wet.
- CNV (Choroidal Neovascularization): The abnormal growth of new, fragile blood vessels in the choroid layer beneath the retina. These vessels can leak fluid or blood, damaging the retina and causing vision loss, often seen in wet AMD.
- DME (Diabetic Macular Edema): A complication of diabetes where fluid leaks from damaged blood vessels in the retina, causing swelling in the macula. This leads to blurred or distorted central vision.
- CSR (Central Serous Retinopathy): A condition where fluid builds up under the macula, often associated with stress and corticosteroid use. This fluid can cause blurred vision, distortion, and blind spots.
- DR (Diabetic Retinopathy): Damage to the blood vessels in the retina caused by diabetes. It can lead to vision loss if untreated, progressing through stages from mild vessel changes to the growth of abnormal new vessels.
- DRUSEN: Tiny yellow deposits of fatty proteins and cellular debris that accumulate under the retina. They are common with aging, but their presence, size, and number can be an early sign of AMD.
- NORMAL: Refers to an eye with healthy vision and no significant detectable pathology. This implies proper light refraction, a clear lens, and a healthy retina and optic nerve.
- MH (Macular Hole): A small tear or defect in the macula, the central part of the retina responsible for sharp, detailed vision. It can cause distorted or blurred central vision and a blind spot.

The first model I created is based on Gaussian Naïve Bayes, using purely numpy and Python; no further libraries or packages were used to train and predict. This model was solely created for learning and educational purpose.

The second model I created is a Convolutional Neural Network. In addition to a small application I developed at the end that takes an image and predicts which eye condition represents. This model is accurate enough that it could be used in a production environment, of course, with some enhancements.

Libraries used in this project:
- Data tabelization and manipulation: Pandas
- Data type storage: Pickle
- Data storage reading and writing: cv2, os
- Data visualization: matplotlib, seaborn
- Data preprocessing and onehot encoding: sklearn
- CNN model and layers creation: TensorFlow
- Data correlation matrix (confusion matrix): sklearn
- 
