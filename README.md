RECOMMENDATIONS WITH IBM WATSON STUDIO
------------------------------------------
The FIVE major aspects of this project is as follows:

* I. Exploratory Data Analysis
* II. Rank Based Recommendations
* III. User-User Based Collaborative Filtering/Content based
* IV. Matrix Factorization
* V. Extras & Concluding


Aims
----------------------
The aim of this project is to analyse the user articles from `articles_community.csv` and the user interactions from `user-item-interactions.csv` and producing different recommendation engines and analyse their performance.


File Structure
----------------------
* `Recommendations_with_IBM.ipynb` is the solution file

* `top_5.p`: pickle file to test top 5 rank based recommendations
* `top_10.p`: pickle file to test top 10 rank based recommendations
* `top_20.p`: pickle file to test top 20 rank based recommendations
* `user_item_matrix.p`: pickle file to load the user_item matrix
* `data` folder contains the following:
  * `articles_community.csv`: csv file containing the articles
  * `user-item-interactions.csv`: csv file containing user interactions with articles
    * `index.html`: Renders homepage
    * `go.html`: Renders the message classifier
  * `run.py`: Defines the app routes

* `tests` folder contains the following:
    *  `project_tests.py`: contains the unit tests for the solution

* It is recommended you run the solution from a jupyter notebook. Please visit
https://jupyter.org/install for installation guide.

INSTALLATION
----------------------
### Clone Repo

* Clone this repo to your computer.
* For mac please ensure you have xcode or download it from the app store (probably not needed)
* Check jupyter is installed correctly using `jupyter --version` and this should return jupyter version
* `cd` to the location of the project home directory
* Execute `Recommendations_with_IBM.ipynb`



## Credits

Lead Developer - Deoga Kofi


## License

The MIT License (MIT)

Copyright (c) 2020 Deoga Kofi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
