# Grocery List
This code allows users to input a list of URLS with recipes and outputs a csv file with ingredient type, ingredient name, amount and associated recipe.

More information on the background on this work can be found on my blog post here.

# Prerequisites
To run this, code, you need to:
* have installed the latest version of Python
* have a Windows machine
* be connected to the internet

# Using Grocery List on your computer
Download the following files into the same directory
* grocery.py
* sr27asc files to identify food groups (USDA National Nutrient Database for Standard Reference, Release 27)

Create a .txt file in the same directory listing a URL with the recipe on each line. For example:
```
https://thewoksoflife.com/chinese-walnut-cookies/
https://www.justonecookbook.com/japanese-potato-salad/
https://tasty.co/recipe/fluffy-jiggly-japanese-cheesecake
```
# Sources
The ingredient parser in this code uses the open source engine at by [schollz](https://schollz.com/blog/ingredients/).