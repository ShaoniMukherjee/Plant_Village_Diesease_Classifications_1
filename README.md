# Plant_Village_Diesease_Classifications
 Dataset of diseased plant leaf images and corresponding labels
 
### Hi there, I'm Shaoni👋

- 🔭 I just launched my first course on youtube: [Let's Learn Data Science Together!][course]!
- 🌱 I’m currently learning everything 🤣
- 👯 I’m looking to collaborate with other content creators
- 🥅 2022 Goals: Contribute more to Open Source projects
- ⚡ Fun fact about me: I love to draw and cook and code

### Connect with me:

[<img align="left" alt="codeSTACKr | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

<br />

### Languages and Tools:

[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />][webdevplaylist]
[<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />][webdevplaylist]
[<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />][cssplaylist]
[<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />][webdevplaylist]
[<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />][webdevplaylist]
[<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />][webdevplaylist]

<br />
<br />

## Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))

2. Install Python packages

```
pip3 install -r training/requirements.txt
pip3 install -r api/requirements.txt
```

3. Install Tensorflow Serving ([Setup instructions](https://www.tensorflow.org/tfx/serving/setup))

## Training the Model

1. Download the data from [kaggle](https://www.kaggle.com/arjuntejaswi/plant-village).
2. Only keep folders related to Potatoes.
3. Run Jupyter Notebook in Browser.

```bash
jupyter notebook
```

4. Open `training/potato-disease-training.ipynb` in Jupyter Notebook.
5. In cell #2, update the path to dataset.
6. Run all the Cells one by one.
7. Copy the model generated and save it with the version number in the `models` folder.

The agriculture sector can be considered as the backbone for any developing economy. To obtain the maximum
yield from the crops, it is required that farmers should be provided with the best technologies and methodologies. Artificial
intelligence is having its vast applications in various sectors. Due to its ability to perceive the problems, developing the
appropriate reasons for that and to establish optimal solutions for it, artificial intelligence can act as a great aid in addressing
the diseases of crops. The paper presents a brief overview of the application of artificial intelligence in agriculture, its
available techniques for agriculture and highlights the various methods available for the detection of diseases in crops

Artificial intelligence has a huge impact in all Industrial Sectors. Lately, Artificial Intelligence (AI) has
been progressing at an outstanding speed. AI accomplished solving numerous problems and saving a
profitable resource by minimizing environmental deterioration. Artificial Intelligence is making a revolution
in agriculture by replacing traditional methods by using methods that are more efficient and helping the
world to become a better place [1]. Agriculture is the principal foundation of subsistence for about 58% of
India's population. The population is expanding enormously with this expansion the interest of food and
business is likewise expanding. Intervening of AI in Agriculture is serving farmers to recover their farming
efficiency and diminish environmental hostile influences [2]. Disease infection is the main drawback of
Agriculture. Due to this drawback, the Quality and Quantity of agriculture products are degraded [3]. To
identify and detect the disease on agriculture product, the AI technique is introduced. In this paper, we are
presenting a survey for application of artificial intelligence in detection of diseases in agriculture.

This project aims to determine plant diesease using AI, we have used Deep learning techniques to find out if the leaves are healthy or not.
Currently the project aims to predict Potato and Bell Paper dieseases. However, the main aim is to use the app in all kitchen vegetables.

Source Paper which motivated me to this project:-https://www.turcomat.org/index.php/turkbilmat/article/download/1581/1335#:~:text=To%20perform%20plant%20disease%20detection,image%20to%20our%20AI%20system.

Inspiration: https://cloud.google.com/blog/products/ai-machine-learning/how-to-serve-deep-learning-models-using-tensorflow-2-0-with-cloud-functions

![potato!](https://github.com/ShaoniMukherjee/Plant_Village_Diesease_Classifications_1/blob/main/Potato_Diesease_classifications/training/PlantVillage/Potato___Early_blight/001187a0-57ab-4329-baff-e7246a9edeb0___RS_Early.B%208178.JPG)

![healthy!](https://github.com/ShaoniMukherjee/Plant_Village_Diesease_Classifications_1/blob/main/Potato_Diesease_classifications/training/PlantVillage/Potato___healthy/00fc2ee5-729f-4757-8aeb-65c3355874f2___RS_HL%201864.JPG)

![early!](https://github.com/ShaoniMukherjee/Plant_Village_Diesease_Classifications_1/blob/main/Potato_Diesease_classifications/training/PlantVillage/Potato___Late_blight/0051e5e8-d1c4-4a84-bf3a-a426cdad6285___RS_LB%204640.JPG)
