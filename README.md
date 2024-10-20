# Bangalore Properties Price Prediction 💵🏡

<p>
<img src="https://img.shields.io/badge/Python-239120?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/numpy-%23013243.svg?logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-%23150458.svg?logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter%20Notebook-Orange&logo=Jupyter"/>
<img src="https://img.shields.io/badge/Kaggle-blue?logo=kaggle&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" />
<img src="https://img.shields.io/badge/html5-E34F26?logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/css3-1572B6?logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=white" />
<img src="https://img.shields.io/badge/GIT-E44C30?logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/prettier-1A2C34?logo=prettier&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-563D7C?logo=github-actions&logoColor=white"/>
</p>

<p>In this comprehensive data science and machine learning project, I developed a model to predict house prices in Bangalore After fine-tuning the hyperparameters and conducting cross-validation, I discovered that Linear Regression was the most effective approach. The model achieved an impressive 86% accuracy in predicting prices. I utilized the Bangalore prices dataset sourced from Kaggle for this analysis.</p>

## Contents
- [Installation](#installation)
- [Folder Structure](#folder-structure-)
- [Usage](#usage-)
- [Features](#features-)
- [Contribute](#contribute-)
- [License](#license-)

# here Come image of web

## Dive to details
Hope you interested on this, Follow me 👞:-

### Installation

1. **Clone the Repository: Clone this repository to your local machine using the following command:**

    ```
    git clone https://github.com/fasinfasi/Real-Estate-Prediction.git
    cd Real-Estate-Prediction
   ```
2. **Setup Virtualenv (Windows)**:
   ```
   pip install virtualenv
   virtualenv venv
   .\venv\Scripts\Activate
   ```
   **Setup Virtualenv (mac/Linux)**:
   ```
   pip install virtualenv
   virtualenv venv
   source venv/bin/activate
   ```

3. **Install Dependencies:** Install the required Python packages using `pip`:
   ```
   pip install -r requirements.txt
   ```

4. **Run the Development Server:** Start the development server:
   ```
   python server/server.py
   ```

5. **Access the Website:** 

    Open the `app.html` file in the ***client*** folder on the web browser to access the Website.

## Folder Structure 📁

* <b>client : This contains interface  website code</b> 
* <b>server: Contains the Python flask server-related code</b>
* <b>model: Contains Python notebook for model building and json file</b>

## Usage 💡

- **Enter Property Details:**
  - Go to the home page of the website.
  - Provide the following details in the input form:
    - **Area**: Input area of the property in Sqft (e.g., 1000, 2300, 3250, etc.).
    - **Number of attributes**: Select the number of attributes (e.g., 1BHK, 2BHK, 3BHK, etc.).
    - **BHK**:<br>
      -> **B** means the number of Bedrooms<br>
      -> **H** refers how many hall the house has.<br>
      -> **K** represent the number of kitchen.<br>
  
- **Choose Location:**
  - Select the **location** of the house from the dropdown menu. Locations include like Rajaji Nagar, Indiranagar, Basavanagudi, etc.

- **Get the Estimated Price:**
  - Click the **"Estimate Price"** button after entering all the details.
  - The estimated price of the house, based on the features and location, will be displayed.

- **Refine Your Search:**
  - You can adjust any of the inputs (such as the number of rooms or location) and click the **"Estimate Price"** button again for an updated price prediction.

## Features ✨

- **Real-time Price Estimation**: Provides instant estimates for house prices based on user input (bedrooms, halls, kitchens, etc.) and location.
- **Location-based Predictions**: The estimation algorithm factors in the Bangalore, giving accurate location-based pricing.
- **User-friendly Interface**: Simple and intuitive input form for users to easily enter property details.
- **Customizable Searches**: Allows users to modify input values (such as rooms or location) and get updated price predictions instantly.
- **Lightweight and Fast**: The website is designed to load quickly and provide estimates without delays.

## Contribute 👬

I welcome contributions from the community! If you'd like to contribute to this project, please follow these guidelines:

**1. Fork Repository:**
  - Fork repositoryto you own GitHub account.

**2. Create a Branch:**
  - Create a new branch for your feature or bug fix:
    ```
    git checkout -b your-feature-branch
    ```
**3. Make Changes:**
  - Implement your changes and commit them:
    ```
    git add .
    git commit -m "Your commit message"
    ```
**4. Push to Your Fork:**
   - Push your changes to your forked repository:
     ```
     git push origin your-feature-branch
     ```
**5. Create a Pull Request:**
   - Submit a pull request to the main repository, linking to your feature branch.

**6. Review and Feedback:**
   - Be prepared to address any feedback or suggestions from the maintainers.

#### Additional Guidelines:
  - Follow coding conventions: Adhere to the project's coding style and formatting guidelines.
  - Write clear and concise commit messages: Explain the changes you've made.
  - Test your changes thoroughly: Ensure your contributions don't introduce new bugs.
  - Respect the project's license: Your contributions should comply with the project's license terms.

By following these guidelines, you can help improve this project and contribute to its success.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.


💖 Thank you for checking out this project! We hope you find it useful and easy to integrate into your workflow.

Stay tune, I will bring you something new 🎆
