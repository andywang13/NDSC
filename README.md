# National Data Science Challenge 2019
This is the largest data science [competition](https://careers.shopee.sg/ndsc/) in Singapore hosted by [Shopee](https://shopee.sg/). The competition contains two categories: Beginner and Advanced. This repository is about my solution to the beginner category which is to classify e-commerce products based on image and text data. The competition overview can be found on [Kaggle](https://www.kaggle.com/c/ndsc-beginner). This is the first deep learning project at this scale that I've dived into and a lot of techniques I've utilized in my solution are picked up along the way. The solution itself is not perfect, but I believe this could serve as a good starting point for tons of data enthusiasts just like me who are ready to learn and draw insigths from data. The final score on the leaderbord is not top-notch but satisfactory (top 30%). 

The goal of this repository is to mark down what I've learned throughout the competition and to share my 2 cents with other data enthusiasts. One of the key takeaways for me is a better understanding of how batch processing handled in Keras. I've posted a gentle introduction to batch processing in Keras on Medium which can be found here.Feel free to drop a line with your questions. Your recommendations are most welcome.

The model pipeline of my solution consists of three parts:

1. CNN for image data
2. MLP for text data
3. Logistic Regression for model stacking

Highlights of the solution:

1. able to classify the products without knowing the broad categories beforehand (although they are already indicated in the image path in the test data, which is OK in the competition but may not be the case in real world)
2. used customized Sequence object to handle batch processing, which tested to be faster than Keras built-in methods like flow_from_directory and flow_from_dataframe

Lastly, I would like to experess my special thanks to [Shopee](https://shopee.sg/) for organizing such an amazing and fruitful competition.

Feel free to drop a line with your questions. Your recommendations are most welcome.
