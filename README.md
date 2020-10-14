# Face Mask Detection With Hardware Support

## Project Purpose and Goal
WHO has advised the use of masks as a part of a comprehensive package of the prevention and control measures that can limit the spread of certain respiratory viral diseases, including COVID-19. Masks can be used either for protection of healthy persons or for source control (worn by an infected individual to prevent onward transmission). Therefore, the widespread use of masks will reduce the number of cases and deaths around the world.
However, along with wearing the mask, the way in which the mask is worn also matters. Many people wear the mask in wrong manner, which actually is of no use as they are still in a position to get infected. So, I came up with a way to solve this— Face Mask Detector and Validator. This system can be used in shopping malls, offices, schools, and railway stations where masks are mandatory. 
The machine is built from using Convolution Neural Network model and performs the following tasks:
1. It Tells if the person is wearing mask or not
2. If the person is wearing a mask, it tells whether he/she is wearing the mask in correct fashion or not.

## About the Dataset:
This dataset is created using the merge of:
1. MaskedFace-Net Dataset : https://github.com/cabani/MaskedFace-Net
2. Some Images from dataset by Prajna. 

So overall, the dataset, present in the 'dataset' folder of the repository contains of two folders:
1. with_mask: Having 3719 images in it
2. without_mask: Having 3737 images in it.

## How to run the code?:

1. Install Anaconda from https://docs.anaconda.com/anaconda/install/windows/ : Installing Anaconda means you are getting a version of Python installed (Anaconda has Python + >450 modules)

2. Open Anaconda Navigator to download all the dependencies required for the project (all the requirements are listed under the project_requirements.txt file):
-> Just go to your directory in the Navigator, and run "pip install -r project_requirements.txt" command.

![Anaconda Prompt](https://github.com/piyushsharma220699/Face-Mask-Detection-Using-Hardware/blob/main/other_images/anaconda_prompt.png)

3. Then in Anaconda: 
Open Jupyter Notebook,
Go to creating_model.ipynb and run all the cells!
(This might take a few minutes to run the file and create the model)
