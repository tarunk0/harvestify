# Harvestify  : A WebApp for Agriculturists.
#### A simple ML and DL based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

## Table of Content:
  * [Disclaimer](#disclaimer)
  * [Live Demo](#live-demo)
  * [Motivation](#motivation)
  * [Built with](#built-with)
  * [How to use](#how-to-use)
  * [Demo](#demo)
  * [Bug Request](#bug-request)
  * [Future scope of project](#future-scope-of-project)



### Disclaimer:
This is a POC(Proof of concept) kind-of project. The data used here comes up with no guarantee from the creator. So, don't use it for making farming decisions. If you do so, the creator is not responsible for anything. However, this project presents the idea that how we can use ML/DL into precision farming if developed at large scale and with authentic and verified data.

### Live Demo: 
Click [here](https://harvestify-tarun.herokuapp.com/) to access the website. 

### Motivation:
- Farming is one of the major sectors that influences a country’s economic growth. 

- In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield. 

- In this project, I present a website in which the following applications are implemented; Crop recommendation, Fertilizer recommendation and Plant disease prediction, respectively. 

- In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow. 

- For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements. 

- For the last application, that is the plant disease prediction application, the user can input an image of a diseased plant leaf, and the application will predict what disease it is and will also give a little background about the disease and suggestions to cure it.


## Built with:
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>
<code><img height="30" src="https://cdn.iconscout.com/icon/free/png-256/heroku-225989.png"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pytorch/pytorch/39fa0b5d0a3b966a50dcd90b26e6c36942705d6d/docs/source/_static/img/pytorch-logo-dark.svg"></code>

## How to use:
- Crop Recommendation system: Enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity, temperature data is fetched.

- Fertilizer suggestion system: Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

- Disease Detection System: Upload an image of leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest you how to prevent/cure the disease accordingly.
Note that, for now it only supports following crops

<details>
  <summary>Supported crops
</summary>

- Apple
- Blueberry
- Cherry
- Corn
- Grape
- Pepper
- Orange
- Peach
- Potato
- Soybean
- Strawberry
- Tomato
- Squash
- Raspberry
</details>

## DEMO

- ### Crop recommendation system

![demo](https://media.giphy.com/media/90JbjdAa5nDq3TJh5u/giphy.gif)

- ### Fertilizer suggestion system

![demo](https://media.giphy.com/media/FLftUXMFo8N2bBjAXq/giphy.gif)


- ### Disease Detection system
![demo](https://media.giphy.com/media/NnMwEp2tGZdfnJbyjr/giphy.gif)



## Bug Request: 
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/tarunk0/harvestify/issues) here by including your search query and the expected result.

## Future scope of project: 
* Optimize Flask app.py
* Front-End 
