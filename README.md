<h1 align="center"> Machine Learning Portfolio </h1>
<h3 align="center"> Jen Alchimowicz </h3>


</br>

<p align="center">
  <img width="600" src=https://user-images.githubusercontent.com/74935134/182331275-43f679b7-2531-43f0-84ad-57b7eaf73588.gif>
</p>


<p align="center">
  <a href="https://www.linkedin.com/in/jedrzej-alchimowicz-b972a0151/"> <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white?"> </a>
  <a href="https://medium.com/@jedrzejalchimowicz"> <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"> </a>
  <a href="https://github.com/JenAlchimowicz"> <img src="https://img.shields.io/badge/Github%20Repos-8-success?logo=github&style=for-the-badge"> </a>
  <a href="https://fastapi.tiangolo.com"> <img src="https://img.shields.io/badge/Completed%20Projects-20%2B-success?logo=python&style=for-the-badge"> </a>
  <a href="https://docs.pytest.org/en/7.1.x/contents.html"> <img src="https://img.shields.io/badge/Years%20of%20experience-2%2B-blue?logo=bookmeter&style=for-the-badge&logoColor=white"> </a>
</p>


## :book: Table of contents
<ol>
  <li><a href="#projects"> ➤ Projects </a></li>
    <ul><br/>
      <li><a href="#computer-vision"> Computer Vision </a></li>
        <ul>
          <li><a href="#emotion-recognition-api"> Emotion Recognition API </a></li>
          <li><a href="#satellite-kaggle"> Semantic segmentation for satellite imagery - Kaggle competition </a></li>
          <li><a href="#ftu-segmentation"> Functional Tissue Unit Segmentation (HuBMAP + HPA) </a></li>
        </ul><br/>
      <li><a href="#machine-learning"> Machine Learning </a></li>
        <ul>
          <li><a href="#ml-fantasy-serie-a"> Predicting player scores in fantasy football with machine learning </a></li>
          <li><a href="#hackathon-cities"> World Data League hackathon </a></li>
        </ul><br/>
      <li><a href="#reinforcement-learning"> Reinforcement Learning </a></li>
        <ul>
          <li><a href="#marl-vdn"> Multi Agent Reinforcement learning - simulating collaboration with VDN </a></li>
          <li><a href="#rl-snake"> Playing Snake with Reinforcement Learning </a></li>
        </ul><br/>
      <li><a href="#gnn"> Graph Neural Networks </a></li>
        <ul>
          <li><a href="#gnn-rec-sys"> GNN-based Recommender System </a></li>
        </ul><br/>
      <li><a href="#NLP"> NLP </a></li>
        <ul>
          <li><a href="#disaster-tweets-kaggle"> Introduction to NLP with disaster tweets detection </a></li>
        </ul><br/>
    </ul>
    <li><a href="#academic-achievements"> ➤ Academic achievements </a></li>
    <li><a href="#courses"> ➤ Completed courses </a></li>  
</ol>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h1 align="left" id="projects"> Projects </h1>

<h2 id="computer-vision"> Computer Vision </h2>

<h3 id="emotion-recognition-api"> Emotion Recognition API </h3>

In this project I developed a system that identifies faces in an image or video and classifies each face into one of the 7 emotions: ['neutral', 'happy', 'sad', 'surprise', 'fear', 'disgust', 'anger', 'contempt']. The project is tested and wrapped into an API.

**Date:** July 2022 <br/>
**Link:** https://github.com/JenAlchimowicz/Emotion-Recognition-Api

<p align="center">
  <img width="400" alt="Screenshot 2022-07-29 at 16 38 23" src="https://user-images.githubusercontent.com/74935134/181783667-e4b01e3e-d742-4065-bb65-51a6065582b1.png">
</p>

<table>
<tbody>
  <tr>
    <td> <b> Languages: </b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts: </b> </td>
    <td> Facial Emotion Recognition, Object Detection, Image Classification, API, testing, continous integration </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> PyTorch, OpenCV, pytest, FastAPI, pyYAML, pandas, numpy </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Visual Studio Code, GitHub, GitHub Actions, black code formatter </td>
  </tr>
</tbody>
</table>

<br/>

<p align="center">
  ________________________________________
</p>

<br/>

<h3 id="satellite-kaggle"> Semantic segmentation for satellite imagery - Kaggle competition </h3>

This project has been developed for Kaggle Competition organised by CentraleSupelec Deep Learning course. The challenge was to segment satellite imagery from areas affected by Hurricane Harvey, to assess the scale of flooding and damages. <br/> `1st place on Kaggle across 38 teams`.

**Date:** December 2021 <br/>
**Link:** https://github.com/JenAlchimowicz/Semantic-segmentation-with-PyTorch-Satellite-Imagery

<p align="center">
  <img width="800" alt="segmentation_mask_example" src="https://user-images.githubusercontent.com/74935134/182353450-5d131511-0223-489b-a92f-ef43d83fc481.png">
</p>

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts: </b> </td>
    <td> Semantic Segmentation, Satellite Imagery, UNet from scratch, Dice coefficient, Focal Loss, Transfer Learning</td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> PyTorch, PIL, segmentation_models_pytorch, pandas, numpy, matplotlib </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Google Colab, Jupyter Notebook </td>
  </tr>
</tbody>
</table>

<br/>

<p align="center">
  ________________________________________
</p>

<br/>

<h3 id="ftu-segmentation"> Functional Tissue Unit Segmentation (HuBMAP + HPA) </h3>

Kaggle challenge organised by [The Human BioMolecular Atlas Program](https://hubmapconsortium.org) and [The Human Protein Atlas](https://www.proteinatlas.org). The task was to perform segmentation on high-dimensional biopsy samples to identify Functional Tissue Units. The key challenge was to overcome domain shift between train and test sets - train set used a different type of staining than test set. <br/>
**Challenge ongoing, code not yet published**

**Date:** August 2022 - ongoing <br/>
**Link:** https://www.kaggle.com/competitions/hubmap-organ-segmentation

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/74935134/182356702-60731479-1c7d-4562-bee3-743b99ad39df.png">
</p>


<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts: </b> </td>
    <td> Semantic Segmentation, Domain shift, Clinical data, High-dimensional imagery, Stain normalization </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> PyTorch, OpenCV, Albumentations, pandas, numpy </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Kaggle notebooks </td>
  </tr>
</tbody>
</table>

<br/>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br/>

<h2 id="machine-learning"> Machine Learning </h2>

<h3 id="ml-fantasy-serie-a"> Predicting player scores in fantasy football with machine learning </h3>

The goal of the project is to recommend high ROI football players in the Fantasy Serie A game. Based on three data sources, two machine learning models predict player scores in the next week's game. The predicted scores are then divided by the players' prices in Fantasy Serie A to identify low-cost, high-performance players that are likely to perform well in the upcoming game. Rules of Fantasy Football can be found [here](https://fantaera.com/regolamento) and [here](https://www.premierleague.com/news/1252542). After the project, I wrote an article explaining the techniques used, which can be found [here](https://medium.com/@jedrzejalchimowicz/tackle-time-series-forecasting-with-supervised-machine-learning-a-step-by-step-guide-in-python-a5510063f8c9).

**Date:** January 2022 <br/>
**Link:** https://github.com/JenAlchimowicz/Predicting-player-scores-in-Fantasy-Serie-A-using-Machine-Learning

<a href="url"><img src="https://user-images.githubusercontent.com/74935134/182358658-07b91ea4-5e3e-4408-8828-8fe34b06f0f7.png" align="left" height="240" width="285" ></a>
<br/>
<a href="url"><img src="https://user-images.githubusercontent.com/74935134/182358648-acbdf500-3eee-4754-8630-8c9cb1b9436b.png" align="right" height="180" width="490" ></a>
<br/><br/><br/><br/><br/><br/><br/><br/><br/>

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts:</b> </td>
    <td> Random Forest, ElasticNet Regression, Web scrapping, Feature Engineering, Forcasting using supervised ML </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> scikit-learn, pandas, numpy, matplotlib, requests, BeautifulSoup </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Jupyter notebooks </td>
  </tr>
</tbody>
</table>

<br/>

<p align="center">
  ________________________________________
</p>

<br/>

<h3 id="hackathon-cities"> World Data League hackathon </h3>

The hackathon consisted of two python projects, first one focusing on citizens’ mobility patterns and second one on predicting traffic flow.
**Submission made to world data league, however, codes are not available anymore**

**Date:** March 2021 <br/>
**Link:** https://www.worlddataleague.com

<p align="center">
  <img width="300" src="https://user-images.githubusercontent.com/74935134/182391182-27293471-3513-43ef-bea8-c69257ca6317.png">
</p>


<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts:</b> </td>
    <td> Supervised ML, Clustering, Smart city, Geospatial data, Signal processing </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> Pandas, ipyleaflet, geopy, scipy.signal, scikit-learn, numpy </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Jupyter notebooks </td>
  </tr>
</tbody>
</table>

<br/>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br/>

<h2 id="reinforcement-learning"> Reinforcement Learning </h2>

<h3 id="marl-vdn"> Multi Agent Reinforcement learning - simulating collaboration with VDN </h3>

The goal of the project was to simulate collaborative behaviour in a custom multi-agent reinforcement learning ([MARL](https://en.wikipedia.org/wiki/Multi-agent_reinforcement_learning)) environment. I look at two types of algorithms: `Independent Q-Learning (IQL)` and `Value Decomposition Network (VDN)`. The results are shown below. We can see clear collaborative behaviour from VDN, while the independent learning approach leads to more individualistic, greedy behaviour:

**Date:** March 2022 <br/>
**Link:** https://github.com/JenAlchimowicz/Multi-Agent-Reinforcement-Learning-simulating-collaboration-with-VDN-and-IQL

VDN             | IQL
:-------------------------:|:-------------------------:
<a><img src="https://user-images.githubusercontent.com/74935134/161282878-4cc5a9cb-c68a-4e93-8a12-e50dfb491263.gif" align="middle" width="250" height="250"/>  |  <a><img src="https://user-images.githubusercontent.com/74935134/161281461-926ef432-d1c1-4a29-97be-c184871dce8b.gif" align="middle" width="250" height="250"/>
  
<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts:</b> </td>
    <td> Multi Agent Reinforcement Learning, Value Decomposition Network, Independent Q-learning, OpenAI Gym environment </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> gym, numpy, Pytorch, matplotlib </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Visual Studio Code, Jupyter notebooks </td>
  </tr>
</tbody>
</table>

<br/>

<p align="center">
  ________________________________________
</p>

<br/>

<h3 id="rl-snake"> Playing Snake with Reinforcement Learning </h3>

Project developed to get a basic understanding of reinforcement learning. Topics covered: custom RL environment for snake game based on OpenAI Gym, RL agents implemented from scratch and Model performance comparison (greedy, e-greedy, Q-learning, expected SARSA and more).

**Date:** February 2022 <br/>
**Link:** https://github.com/JenAlchimowicz/Reinforcement-Learning-Snake-from-scratch

<p align="center">
  <img width="350" src="https://user-images.githubusercontent.com/74935134/153014017-58b8dbdd-eed8-4cab-9c62-c87dcfe9cf20.gif">
</p>

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts:</b> </td>
    <td> Reinforcement Learning, Tabular RL, algorithms: greedy, epsilon-greedy, Q-learning, SARSA, RL environments </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> gym, numpy, matplotlib </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Visual Studio Code, Jupyter notebooks </td>
  </tr>
</tbody>
</table>

<br/>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br/>

<h2 id="gnn"> Graph Neural Networks </h2>

<h3 id="gnn-rec-sys"> GNN-based Recommender System </h3>

The classical approach to recommender systems is to use either User-to-User or Item-to-Item Collaborative Filtering, or a combination of the two. These approaches have been extensively covered from both research and business use case angles. Next, graph-based approaches have been proposed. However, they typically employed a multi-stage pipeline, consisting of separate graph feature extraction models and link prediction models, which were treated and trained separately. In this project we explore an end-to-end solution, which contrary to those early approaches trains the entire pipeline as one piece. Developed for CentraleSupelec Machine Learning in Network Sciences course. **Credits:** Nevina Dalal, Enrico Burigana, Thomas Gak-Deluen, Jen Alchimowicz

**Date:** April 2022 <br/>
**Link:** https://github.com/JenAlchimowicz/End-to-end-GNN-based-recommender-system

<br/>
  
<p align="center">
  <img width="550" src="https://user-images.githubusercontent.com/74935134/164025710-5b3ae7b4-ca65-4d5d-ba5f-559a67c92377.png">
</p>

  <br/>

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts:</b> </td>
    <td> Graph Neural Networks, Recommender Systems, Graph Attention Network, Heterogenous Graphs, Bipartite Graphs </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> PyTorch geometric, networkx, pandas, numpy, PyTorch </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Jupyter notebooks, Google Colab </td>
  </tr>
</tbody>
</table>

<br/>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br/>

<h2 id="NLP"> Natural Language Processing (NLP) </h2>

<h3 id="disaster-tweets-kaggle"> Introduction to NLP with disaster tweets detection </h3>

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programmatically monitoring Twitter (i.e. disaster relief organizations and news agencies). The purpose of this project is to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. Classification is done primarily by the content of the tweet.

**Date:** December 2020 <br/>
**Link:** https://github.com/JenAlchimowicz/NLP-with-Disaster-Tweets-Kaggle-Competition

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key&nbsp;Concepts:</b> </td>
    <td> Supervised ML, text processing, data visualisation, ML evaluation metrics </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> pandas, scikit-learn, numpy, nltk, matplotlib, seaborn </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Jupyter notebooks </td>
  </tr>
</tbody>
</table>

<br/>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br/>

<h1 align="left" id="academic-achievements"> Academic achievements </h1>
 
### [Master in Data Sciences and Business Analytics](https://www.essec.edu/en/program/mscs/master-data-sciences-business-analytics/) at ESSEC & CentraleSupelec
  
<ul>
  <li> Highest grade in cohort from Deep Learning and Reinforcement Learning courses </li>
  <li> 1st place among 38 teams in Deep Learning competition </li>
  <li> 3rd place among 25 teams in Machine Learning competition </li>
  <li> 17.64/20 GPA</li>
</ul>

### [Bachelor in Business Management (BSc)](https://www.surrey.ac.uk/undergraduate/business-management) at University of Surrey

<ul>
  <li> Overall grade: High First class (highest possible grade) </li>
  <li> Member of Surrey Stars </li>
  <li> 91% GPA from Finance courses </li>
</ul>

<br/>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br/>

<h1 align="left" id="courses"> Completed courses </h1>

- [Machine Learning](https://www.coursera.org/specializations/machine-learning-introduction), Stanford Online, by Andrew Ng
- [Deep Learning Specialisation](https://www.coursera.org/specializations/deep-learning), Coursera, by Andrew Ng
- [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/), Udemy, by Jose Portilla
  
All certificates available on my [Linkedin](https://www.linkedin.com/in/jedrzej-alchimowicz-b972a0151/)
  
