# Sympto Tracker - Predcit Disease, Prevent Disease.

<center><img src="https://user-images.githubusercontent.com/100853494/236436577-84e920c1-c6c0-4610-8aea-3b7f004a6dfd.png" width="800" height="auto"></center>

## Live Demo
### Check out the live demo of Sympto Tracker <a href="https://sympto-tracker.vercel.app/"><img src="https://static.vecteezy.com/system/resources/previews/009/384/880/non_2x/click-here-button-clipart-design-illustration-free-png.png" width="120" height="auto"></a>

Sympto-Tracker is a web application that allows users to track their symptoms and predict the likelihood of developing certain diseases. The application is built using React, Flask, and RStudio, and currently supports the prediction of the following diseases:

- `Liver Cirrhosis`
- `Mesothelioma`
- `Chronic Kidney Disease`
- `Coronary Heart Disease`
- `Diabetes Mellitus`

For predicting the disease diagnosis we used Supervised Binary Classification Machine Learning models, and used the following algorithms:

- `Logistic Regression`
- `Support Vector Machine`
- `XGBoost`

## Tech Stack

|  | Name | Use Case |
| ------------- | ------------- | ------------- |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png" width="50" height="50"> | React.js | Frontend Web Framework |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/1200px-Node.js_logo.svg.png" width="50" height="50"> | Node.js | Runtime Environment |
| <img src="https://w7.pngwing.com/pngs/166/342/png-transparent-flask-python-bottle-web-framework-web-application-flask-white-monochrome-shoe.png" width="50" height="50"> | Flask | Backend Web Framework |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/935px-Python-logo-notext.svg.png" width="50" height="50"> | Python | Machine Learning Models |
| <img src="https://cran.rstudio.com/Rlogo.svg" width="50" height="50"> | R | Data Analysis and Visualization |

## Installation

To run the application, you will need to have `Node.js`, `Python`, and `R` installed on your computer.

1. Clone the repository:

   `git clone https://github.com/harshitv804/sympto-tracker.git`
   
2. Install the dependencies for the frontend and backend:

   `cd sympto-tracker/frontend
   npm install`

   `cd ../backend
   pip install -r requirements.txt`

3. Start the frontend and backend servers:

   `cd sympto-tracker/frontend
   npm start`

   `cd ../backend
   python app.py`
   
4. Navigate to `http://localhost:3000` in your web browser to use the application.

## Usage

To use Sympto-Tracker, simply enter your symptoms into the form on the home page and click `Predict`. The application will use machine learning algorithms to predict the likelihood of developing each of the supported diseases based on your symptoms.

## Credits

Sympto-Tracker was developed by:

| | Name | Profile Link |
| ------------- | ------------- | ------------- |
| <img src="https://avatars.githubusercontent.com/u/100853494?v=4" width="50" height="50">  | Harshit V  | https://github.com/harshitv804  |
| <img src="https://avatars.githubusercontent.com/u/74135002?v=4" width="50" height="50">  | Anto Vimalan  | https://github.com/vimalds15  |
| <img src="https://avatars.githubusercontent.com/u/70755637?v=4" width="50" height="50">  | Prawin RP  | https://github.com/PRAWIN392  |
| <img src="https://avatars.githubusercontent.com/u/95230817?v=4" width="50" height="50">  | Aniket Kumar  | https://github.com/ak736  |

If you have any questions or feedback, please reach out to [harshitv804@gmail.com]

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
