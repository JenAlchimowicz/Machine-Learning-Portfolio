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
    <li><a href="#courses"> ➤ Completed courses </a></li>
    <li><a href="#courses"> ➤ Academic achievements </a></li>
</ol>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h1 align="left" id="projects"> Projects </h1>

<h2 id="computer-vision"> Computer Vision </h2>

<h3 id="emotion-recognition-api"> Emotion Recognition API </h3>

In this project I developed a system that identifies faces in an image or video and classifies each face into one of the 7 emotions: ['neutral', 'happy', 'sad', 'surprise', 'fear', 'disgust', 'anger', 'contempt']. The project is tested and wrapped into an API.

Link: https://github.com/JenAlchimowicz/Emotion-Recognition-Api

<p align="center">
  <img width="400" alt="Screenshot 2022-07-29 at 16 38 23" src="https://user-images.githubusercontent.com/74935134/181783667-e4b01e3e-d742-4065-bb65-51a6065582b1.png">
</p>

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key Concepts:</b> </td>
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

</br>

<h3 id="satellite-kaggle"> Semantic segmentation for satellite imagery - Kaggle competition </h3>

This project has been developed for Kaggle Competition organised by CentraleSupelec Deep Learning course. The challenge was to segment satellite imagery from areas affected by Hurricane Harvey, with the goal of assessing the scale of flooding and damages. <br/> **1st place on Kaggle across 38 teams.**

Link: https://github.com/JenAlchimowicz/Semantic-segmentation-with-PyTorch-Satellite-Imagery

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
    <td> <b>Key Concepts:</b> </td>
    <td> Semantic Segmentation, Satellite Imagery, UNet from scratch, Dice coefficient, Focal Loss, Transfer Learning </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> PyTorch, PIL, segmentation_models_pytorch, pandas, numpy, matplotlib </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Google Colab + CUDA, Jupyter Notebook </td>
  </tr>
</tbody>
</table>

</br>

<h3 id="ftu-segmentation"> Functional Tissue Unit Segmentation (HuBMAP + HPA) </h3>

Kaggle challenge organised by [The Human BioMolecular Atlas Program](https://hubmapconsortium.org) and [The Human Protein Atlas](https://www.proteinatlas.org). The task was to perform segmentation on high dimensinal biopsy samples to identify Functional Tissue Units. Key challenge was to overcome domain shift between train and test sets - train set used a different type of staining than test set. <br/>
**Challenge ongoing, code not yet published**

Link: https://www.kaggle.com/competitions/hubmap-organ-segmentation

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
    <td> <b>Key Concepts:</b> </td>
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



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="machine-learning"> Machine Learning </h2>

<h3 id="ml-fantasy-serie-a"> Predicting player scores in fantasy football with machine learning </h3>

The goal of the project is to recommend high ROI football players in the Fantasy Serie A game. Based on three data sources, two machine learning models predict player scores in the next week's game. The predicted scores are then divided by the players' prices in Fantasy Serie A to identify low-cost, high-performance players that are likely to perform well in the upcoming game. Rules of Fantasy Football can be found [here](https://fantaera.com/regolamento) and [here](https://www.premierleague.com/news/1252542). After the project I wrote an article explaining the techniques used, which can be found [here](https://medium.com/@jedrzejalchimowicz/tackle-time-series-forecasting-with-supervised-machine-learning-a-step-by-step-guide-in-python-a5510063f8c9).

Link: https://github.com/JenAlchimowicz/Predicting-player-scores-in-Fantasy-Serie-A-using-Machine-Learning

<a href="url"><img src="https://user-images.githubusercontent.com/74935134/182358648-acbdf500-3eee-4754-8630-8c9cb1b9436b.png" align="left" height="240" width="285" ></a>
<br/>
<a href="url"><img src="https://user-images.githubusercontent.com/74935134/182358658-07b91ea4-5e3e-4408-8828-8fe34b06f0f7.png" align="right" height="180" width="490" ></a>
<br/><br/><br/><br/><br/><br/><br/><br/><br/>

<table>
<tbody>
  <tr>
    <td> <b>Languages:</b> </td>
    <td> Python </td>
  </tr>
  <tr>
    <td> <b>Key Concepts:</b> </td>
    <td> Random Forest, ElasticNet Regression, Web scrapping, Feature Engineering, Forcasting using supervised ML </td>
  </tr>
  <tr>
    <td> <b>Key Libraries:</b> </td>
    <td> scikit-learn, pandas, numpy, matplotlib, requests, BeautifulSoup </td>
  </tr>
  <tr>
    <td> <b>Tools:</b> </td>
    <td> Jupyter notebook </td>
  </tr>
</tbody>
</table>
