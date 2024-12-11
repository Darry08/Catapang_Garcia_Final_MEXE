<h1 align="center"><i>PART 2: ERODING POKEMON IMAGES</i></h1>

## ___INTRODUCTION___

  ### Demonstrating Morphological Erosion

  * **_Morphological erosion_** is a fundamental image processing operation in computer vision. It involves sliding a structuring element across an image, removing pixels at object boundaries. This process shrinks the foreground features of an image, emphasizing the significance of kernel size and shape in altering image features.

  ### Pokemon Images Erosion
  * This project discusses the concept of morphological erosion in terms of **Pokémon images** to present the idea of this technique in a novel and visually appealing way, so that its principles may be better understood. Through erosion with different kernel sizes, this project will demonstrate how it transforms the features of the images. The analysis shows that the morphological erosion is highly versatile and plays a key role in preprocessing images before performing more efficient computational analysis. This approach lets us have insight into how these morphological operations could actually be applied in real-life practice.
  
## _**ABSTRACT**_

* **Objective:** To demonstrate how morphological erosion in computer vision can be utilized by showing how the features of Pokémon images are reduced under different kernel sizes.
* **Approach:** To utilize _Morphological erosion_ as a basis in image processing technique to reduce the boundaries within Pokemon images, used for noise removal, simplification of shapes, and object segmentation.
* **Purpose:** To visualize and analyze how erosion with different kernel sizes affects the transformation of features in the Pokemon images.

## _**PROJECT METHODS**_

* Clone Github File
  * Download the repository from GitHub using the "git clone" command, ensuring access to all project files and dependencies.
* Import Necessary Libraries
  * Load essential Python libraries
* Pokemon Image folder
  * Direct path containing a collection of Pokémon images, used as a dataset for Erosion in OpenCV.
* Processing Images
  * Apply OpenCV techniques to manipulate and analyze images, including resizing, filtering, edge detection, and color space conversions, to prepare them for further tasks.
* Converting to a Pandas Dataframe
  * Transform image data into a structured tabular format using Pandas for easier manipulation and analysis.
* Display Images on the table (Original Image, Canny Images, Eroded Images)
  * **Original Image**: Show the original Pokémon image from the dataset.
  * **Canny Image:** Apply the Canny edge detection algorithm to the image and display the result.
  * **Eroded Image:** Apply morphological erosion to the image and display the result.


## _**CONCLUSION**_

- In this experiment, the concept of **morphological erosion** was demonstrated using **Pokémon Images** as visual examples. We observed how the technique reduced the distinct features of the images by applying erosion with varying kernel sizes. Smaller kernel sizes resulted in subtle transformations, while larger kernels significantly simplified the images by removing finer details and contracting boundaries. This approach pointed out some real applications of morphological erosion in computer vision: removing noise, simplifying the shape, and segmenting an object. The visualization of such effects clearly explained how the erosion process affects the image features, which makes it more practical for preprocessing tasks in image analysis.

## _**ADDITIONAL MATERIALS**_

_**Codes for Eroding Pokemon Pictures**_

![image](https://github.com/user-attachments/assets/a665089f-d7b7-42f6-8d3e-f57b28432505)

![image](https://github.com/user-attachments/assets/dbc9882e-d7b2-4a3c-a1e8-8943f2a936fe)

![image](https://github.com/user-attachments/assets/b398f7ce-cc20-4b3c-bbc9-06a2c4a29a4e)

![image](https://github.com/user-attachments/assets/55f723b6-ff18-417c-818f-0ae31209e799)

![image](https://github.com/user-attachments/assets/5b3e7dc7-dd1f-495b-b9bf-e22c34d60ca7)

![image](https://github.com/user-attachments/assets/a5e6e1a0-b2e9-43b2-a9fa-aa13668b06fe)

_**Sample Results: Eroded Pokemon Pictures**_

* _**Original Images:**_ Display of the original image with its natural colors and structure.

* _**Canny Images:**_ Highlighting the edges in the image. It identifies boundaries by detecting areas of rapid intensity change, emphasizing the edges of the object.

* _**Eroded Images:**_ The erosion operation is performed on the Canny output. This morphological operation reduces the thickness of edges and removes small noise, resulting in a thinner and simplified version of the detected edges.

![image](https://github.com/user-attachments/assets/42d12c9e-6b4d-4fd3-9e13-a011d774678c)

![image](https://github.com/user-attachments/assets/9b193da0-64a0-44d9-ad57-69ae7fc26519)

![image](https://github.com/user-attachments/assets/c3e9e724-769a-4067-8905-9184c82b3a42)

![image](https://github.com/user-attachments/assets/4cde1efd-7d0e-4b77-84d5-25f902431b32)

![image](https://github.com/user-attachments/assets/6e5d9415-57e4-45ef-a3ab-07155d64f77f)

![image](https://github.com/user-attachments/assets/da99f3b3-b6dd-4a14-8ffc-bfb47f3b27ba)

![image](https://github.com/user-attachments/assets/280e6716-31a3-41da-918d-3192a010a0cc)

![image](https://github.com/user-attachments/assets/e3dbc059-1816-44cc-990d-5d972f2a04ad)

![image](https://github.com/user-attachments/assets/7367dd78-e202-48ac-8a24-e96eeef07a86)

![image](https://github.com/user-attachments/assets/32f3fffa-d2c3-489e-9b6a-7de875d48c0a)

![image](https://github.com/user-attachments/assets/e2f85fe1-6234-421c-951d-970afb306f98)

![image](https://github.com/user-attachments/assets/1e0ceb6c-0041-41fb-9e04-01ec94a8660b)

## ___REFERENCES___

* Tree. (n.d.). _faceted abstract background in 3d with shimmering iridescent metallic texture of blue violet and pink_. Pngtree. https://pngtree.com/free-abstract-background

* _10 cute cat pictures that help us get through Monday._ (2021, July 19). Pawlicy Advisor. https://www.pawlicy.com/blog/cat-photos-for-monday/

* Misbah. (n.d.). _GitHub - misbah4064/opencvTutorial: Project Files for OpenCV Tutorial Series_. GitHub. https://github.com/misbah4064/opencvTutorial

* Misbah. (n.d.-a). _GitHub - misbah4064/face_recognition: Repository to assist with face recognition colab notebook_. GitHub. https://github.com/misbah4064/face_recognition.git

* GeeksforGeeks. (2021, September 24). Python OpenCV Find center of contour. GeeksforGeeks. https://www.geeksforgeeks.org/python-opencv-find-center-of-contour/

* Critterman. (2023, November 13). The Spiny Bush Viper | Critter Science. Critter Science. https://critter.science/the-spiny-bush-viper/

* Archaeologists unearth huge ancient winery in central Israel. (2022, October 5). [Video]. NBC News. https://www.nbcnews.com/news/world/gold-coins-hidden-wall-israel-byzantine-empire-rcna50593
