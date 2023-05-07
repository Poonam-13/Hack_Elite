# FramingTone 🌱

A farmer website that leverages deep learning and machine learning algorithms to provide valuable insights and recommendations for farmers 

## Table of Contents 📖
- [About](#About)
- [How to use?](#How to use?)
- [Installation](#installation)
- [Contributing](#contributing)
- [Contact](#contact)

## About 📙

* Farming plays a crucial role in driving a country's economic growth. In countries like India, where a significant portion of the population relies on agriculture for their livelihood, integrating advanced technologies like Machine Learning and Deep Learning into the agricultural sector has become essential. These technologies aim to simplify the farming process and help farmers maximize their crop yields.

* I have developed a website that incorporates various applications to assist farmers in their agricultural practices. 

   * The first application focuses on crop recommendation. Users can provide soil data, and based on this information, the application predicts which crop would be most suitable for their specific conditions.

   * The second application is dedicated to fertilizer recommendation. By inputting soil data and specifying the type of crop they are growing, users can receive personalized recommendations on the nutrients their soil lacks or has in excess. The application provides suggestions for improving the soil quality accordingly.

   * The third application focuses on plant disease prediction. Users can upload an image of a diseased plant leaf, and the application employs machine learning algorithms to identify the disease. It also offers background information about the identified disease and provides suggestions for its treatment.

   * Lastly, if farmers seek information about additional crops, they can utilize the last application. This page retrieves comprehensive information about various crops, enabling farmers to expand their knowledge base.

* Overall, this website aims to leverage technology to enhance agricultural practices by providing crop recommendations, fertilizer suggestions, plant disease identification, and a wide range of information on different crops.

## How to use?

- The Crop Recommendation system can be utilized by entering the relevant nutrient values of your soil, along with the state and city information. It is important to note that the N-P-K (Nitrogen-Phosphorus-Potassium) values should be entered as ratios. For more detailed instructions, please refer to the provided website. Keep in mind that when entering the city name, it is advisable to use common city names as remote cities or towns might not be available in the Weather API, which is used to fetch humidity and temperature data.

- To make use of the Fertilizer suggestion system, input the nutrient contents of your soil and specify the crop you intend to grow. The algorithm will then identify any nutrient deficiencies or excesses in the soil and offer suggestions for purchasing appropriate fertilizers accordingly.

- For the Disease Detection System, simply upload an image of a leaf from your plant. The algorithm will determine the crop type and ascertain whether the plant is healthy or diseased. If a disease is detected, the system will provide information about the cause of the disease and suggest prevention or treatment methods. Please note that the current system only supports certain crops.

- If farmers wish to access information about additional crops, the Crop Information section provides a way to retrieve extensive details about various crops.

## Installation
 - Before proceeding with the following steps, ensure that you have Git, Anaconda, or Miniconda installed on your system. You can then clone the entire project using the command git clone https://github.com/Poonam-13/Hack_Elite.git, or alternatively, you can download the code and unzip it.

 - Please note that the master branch does not contain the updated code required for deployment. To obtain the updated code for deployment, you can use the following command:

 ``` git clone -b deploy https://github.com/Poonam-13/Hack_Elite.git ```
 - The deploy branch exclusively includes the necessary code for deploying the application, while the rest of the code, used for training the models and data preparation, can be accessed from the master branch.

 - For running the project locally, it is highly recommended to clone the deploy branch. If you have the deploy branch cloned, follow the steps below.

- 1.Once the project is cloned, navigate to the directory where it was cloned and open the Anaconda Prompt.
- 2.In the Anaconda Prompt, execute the following block of commands:
    conda create -n Hack_Elite python=3.6.12
    conda activate Hack_Elite
    pip install -r requirements.txt
    
 - Finally, run the project using the command:

    python app.py
- After running app.py, you will be provided with a localhost URL. Open this URL in your web browser to access and utilize the project locally.
- By following these steps, you can set up and run the project on your system using the provided web browser interface.

## Contributing

Contributions are welcome! If you'd like to contribute to the project.

## 🔗Contact

If you have any questions, feedback, or suggestions, please feel free to reach out:
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pooo13/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Poooo_13)
