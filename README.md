# Group 5 Image Classification Project

## Members:
- Gaurav Kharel (kharelg24@vt.edu)
- Omar Nweashe (omarnweashe@vt.edu) 
- Patrick Mountcastle
- Valeria Pozo

## Datasets:

1. Both datasets are available locally [here](https://drive.google.com/drive/u/2/folders/12_N3wohlEbR33qDdGV3b8amnR2uz8iDs)
2. The image dataset for Dogs and Cats can be found [here](https://www.microsoft.com/en-us/download/details.aspx?id=54765)
3. The image dataset for Caltech Birds can be found [here](https://data.caltech.edu/records/65de6-vp158) 


## Instructions to setup and run the project:

### **Folder Setup:**
**1.** Create a local folder on your computer for the project.

**2.** Download the repository source code for both models, **CNN_simple.ipynb** and **KNN_Model.ipynb** in the folder you created.

**3.** If you use the dataset link 1 above to download the images, then you need to download the folders named **PetImages** and **PetImages_Split** into the project folder you created locally, you can skip steps **4, 5, 6, 7, 8, and 9** if you do this step.

**4.** If you decide  to use the original datasets then you need to download datasets links 2 and 3 from above.

**5.** Create a folder and name it **images** in the local project folder.

**6.** In the **images** folder, create 3 sub-folders for each animal **(cat, dog, bird)**.

**7.** For the cat images, you will need to delete image **666.jpg** since it is corrupted.

**8.** For the dog images you need to delete image **11702.jpg** since it is corrupted.

**9.** For the bird images, you will need to extract all the images from the 200 bird-species sub-folders and insert them in the bird file you created in the project file.

### **Notebook Setup:**
**1.** In the second and third cells in both **CNN_simple.ipynb** and **KNN_Model.ipynb** make sure you modify the path variables to their respective values that correspond to your computers.

**2.** For the **output_path** variable, make sure you have a folder designated, it should be on the same level as your **images** folder.

**3.** In **KNN_Model.ipynb**'s fifth cell, make sure to update the **train_dir** and **test_dir** variables accordingly.

**4.** Both notebooks should be ready to be executed after making sure all the import dependencies are installed, the development environment we used is **VSCode**.

### **If problems are faced please reach out to:***

- Omar 571 279 9177
- Gaurav 703 789 3495
