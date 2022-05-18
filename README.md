# Recipe Recommendation Bot
## What's cooking?
![](Images/robo_chef_cartoon.jpeg)
_______________________________________________________________________________________________________________________
## Contributors
- Jihad Al-Hussain
- Shanel Kuchera
- JJ Torres
______________________________________________________________________________________________________________________
## Project Description
- Created a recipe recommendation system by training a computer vision model in keras-tensorflow using a custom convolutional neural network model (CNN).
- Created a python tool that recommends recipes based on ingredients input as images or text.
- Scraping over 5000 recipes from All Recipes using python and beautiful soup.
- Deployed a user-friendly app using the telegram bot API as a front end.

_______________________________________________________________________________________________________________________
## TechStack
| Python | 
| Keras |
| Tensorflow |
| Telegram Bot API |
| [recipe-scrapers By hhursev](https://github.com/hhursev/recipe-scrapers) |
_______________________________________________________________________________________________________________________
## Datasets to be used
- [Fruits and Vegetables Image Recognition Dataset](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)
- [Food Images (Food-101)](https://www.kaggle.com/datasets/kmader/food41)
_______________________________________________________________________________________________________________________
## How to Use the Bot
Before you start:
- install the list of dependicies using pip ```pip install -r requirements.txt```
- Telegram API key [How to get it](https://core.telegram.org/bots/api#authorizing-your-bot)

Simply run the bot using the following command:
- ```python3 telegram-bot-industry-model.py``` 
- or ```python3 telegram-bot-our-model.py ```

experiment and play and have fun ! 
_______________________________________________________________________________________________________________________

## Results from the Project
- Successfully trained and tested the model using keras and tensorflow
    - The model can be improved by using a larger number of images and a more robust model architecture. 
    - Better techniques can be used to improve the model such as transfer learning from an existing vision model.
- Successfully deployed the chatbot using the telegram API 
- Investigated the use of Amazon lex as a backend to provide a better user experience by using the AWS-API as a backend

Here is a Demo of the chatbot in action: 
![](ppt_images/Chef_bot.gif)



