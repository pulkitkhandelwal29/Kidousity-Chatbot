# Kidousity Chatbot
The idea is to specifically tailor the chatbot to satiate the intellectual curiosity of 6–10 year old kids. They will be able to ask questions in the text form and get short, crisp, and accurate answers to their questions in the form of text again. It will help kids in interactive learning and maintaining the curious nature of questioning. Using our chatbot, the kids can get answers to as many questions as they want and get quick responses.

## Running this project

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
virtualenv env
```

That will create a new folder `env` in your project directory. <br><br>
To activate environment, 

1. Command on mac/linux:

```
source env/bin/active
```

2.  Command on Windows:

```
env\Scripts\Activate
```

Then install the project dependencies with

```
pip install -r requirements.txt
```

Now you can run the project with this command

```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

To run RASA server
```
rasa run --cors "*" --enable-api
```

## Screenshots
![7](https://user-images.githubusercontent.com/67990422/167275150-42156c7c-1d92-4cc1-ae4c-8d326b1170b8.PNG)
![8](https://user-images.githubusercontent.com/67990422/167275154-610c7774-9130-4a72-87b2-f2dc9b9e6b32.PNG)
