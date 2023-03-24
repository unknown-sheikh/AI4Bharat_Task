# Wikipedia Translation Application

This application allows a user to enter an article title on Wikipedia. The application collects article data from Wikipedia and lets the users translate the article content into other languages. The application is built using Django and HTML Templates.

##  How to Run Locally 

* Clone the repository 
'https://github.com/unknown-sheikh/AI4Bharat_Task.git'

* Install dependencies

`pip install -r requirements.txt`

* Run the application

`python manage.py runserver`

## Application Flow 

1. User enters the article title in the search bar on the project page along with the target language. 
2. The application fetches the summary article data from Wikipedia and displays the article content in the translation page with translasting summary of the article.
3. The summary of the article also saved in the database.

**Note:** I have also added Django groups with two roles - managers and annotators with differential privacy for both. 



## Application Testing Credentials 

You can use these credentials to test the application locally. Currently, I have not given the feature to create new users so you need to use the credentials of an existing user.

**Superadmin credentials** 
- **username** - admin 
- **password** - admin

**Manager Credentials**
- **username** - manager
- **password** - not-man-123

**Annotator Credentials** 
- **username** - annotator 
- **password** - not-annot-123

# AI4Bharat
