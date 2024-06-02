## Restaurant Review Sentiment Analysis
![](restaurant_image.PNG)

#### Project Overview
The Restaurant Review Sentiment Analysis project utilizes natural language processing techniques and machine learning algorithms to automatically process customer reviews and determine their sentiment polarity. The system is trained on a collected dataset of restaurant reviews and provides real-time feedback through a user-friendly GUI interface.

#### Problem Statement
Restaurants often struggle to efficiently analyze customer feedback, leading to a lack of real-time insights into customer sentiments. This hinders their ability to promptly address concerns, improve services, and maintain customer loyalty.

#### Objectives
1.  Develop an automated sentiment analysis system that accurately classifies restaurant reviews into positive, neutral, and negative categories.
2.  Provide restaurants with real-time feedback on their performance based on customer reviews.
3.  Create a user-friendly GUI interface for easy interaction with the sentiment analysis system.
4.  Utilize logistic regression for accurate sentiment classification.

#### Dataset
The sentiment analysis model is trained using a collected dataset of customer reviews. The dataset consists of review texts that have been preprocessed and formatted to be compatible with the logistic regression algorithm. The preprocessing steps ensure that the data is clean, relevant, and suitable for training the sentiment classification model.

#### Model Training
The logistic regression algorithm is employed to train the sentiment analysis model. The collected dataset is used in its entirety for training, allowing the model to learn from a diverse range of review examples. During the training process, the model identifies patterns and features within the review texts that are indicative of positive, neutral, or negative sentiments.

By training on a comprehensive dataset, the sentiment analysis model acquires the ability to accurately classify new, unseen reviews into the appropriate polarity categories. This enables the system to provide reliable sentiment predictions when presented with new customer reviews.

#### GUI Interface
A user-friendly graphical user interface (GUI) has been developed to facilitate easy interaction with the sentiment analysis system. The GUI allows users to input customer reviews and receive instant feedback on the predicted polarity category. The interface provides a simple and intuitive way to test the performance of the sentiment analysis model.

#### Video Demonstration
To see the Restaurant Review Sentiment Analysis system in action, watch the video demonstration below:

[GUI Demonstration Video](./GUI_REC.mp4)

The video demonstration showcases the ease of use and real-time functionality of the Restaurant Review Sentiment Analysis system. It highlights the system's ability to accurately predict sentiment polarity for various types of reviews, including positive, negative, and neutral examples. The video also demonstrates how the review counts and personalized recommendations sections of the GUI are updated based on the sentiments of the input reviews.

#### Requirements
To run the Restaurant Review Sentiment Analysis system, the following dependencies are required:
-   Numpy
-   Scikit-learn
-   NLTK
-   Tkinter

 These dependencies can be easily installed using the provided ```requirements.txt``` file. Simply run the following command:
```
pip install -r requirements.txt
``` 

#### Usage
To use the Restaurant Review Sentiment Analysis system, follow these steps:
1.  Clone the repository
```
git clone https://github.com/PeterAyan/restaurant-review-sentiment-analysis.git
```
2. Navigate to the project directory. The repository structure is as follows:
- ```Dataset/```: Contains the training datasets used in the project.
-   ```src/```: Contains the source code [Jupyter Notebook](/src/ABSA%20SYSTEM.ipynb) which entails the steps for data preprocessing, model training, and the GUI interface
-   ```requirements.txt```: Lists the required Python dependencies for running the project.
-   ```README.md```: Provides an overview of the project and instructions for running the code.

3.  Install the required dependencies:
```
pip install -r requirements.txt
```
4.  Run the sentiment analysis system by executing the Jupyter Notebook:
```
ABSA SYSTEM.ipynb
```
5. Once the notebook is running, you can interact with the GUI interface. Input customer reviews into the provided text box and click the "Predict" button to obtain the predicted sentiment polarity (positive, negative, or neutral).

#### Conclusion
The Restaurant Review Sentiment Analysis project addresses the need for an automated and efficient system to analyze customer feedback in the restaurant industry. By leveraging machine learning techniques and a user-friendly GUI interface, the system enables restaurants to obtain real-time insights into customer sentiments, empowering them to make data-driven decisions and improve their services.

The logistic regression algorithm, trained on a comprehensive dataset of restaurant reviews, ensures accurate sentiment classification. The GUI interface provides a seamless and intuitive way for users to interact with the system, input reviews, and receive instant feedback on the predicted sentiment polarity.

With this sentiment analysis system, restaurants can proactively monitor customer feedback, identify areas for improvement, and take timely actions to enhance customer satisfaction and loyalty. By harnessing the power of sentiment analysis, restaurants can gain a competitive edge and drive their business growth in the dynamic and challenging food service industry.

Thanks for reading! You can find me on [linkedin](https://www.linkedin.com/in/peter-ayanrinno-73171022a)

