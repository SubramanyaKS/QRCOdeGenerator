# QR CODE AND BAR CODE GENERATOR
This is a simple flask app which generate QRCode and also Bar Code based on the input url given by the user.

## Flask
Flask is a web application framework written in Python. Armin Ronacher, who leads an international group of Python enthusiasts named Pocco, develops it. Flask is based on Werkzeug WSGI toolkit and Jinja2 template engine. Both are Pocco projects.

## Technology used
* ![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
* ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
* ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
* ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
* ![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

## Project Structure
This project has three major parts :

* app.py - This contains Flask APIs that generate the QR code given input.
* template - This folder contains the HTML template (index.html) to allow user to enter the website to convert them into QRCode images.
* static - This folder contains the css folder with style.css file which has the styling required for out index.html file.
* .gitignore - Git ignore patterns are used to exclude certain files in your working directory from your Git history. They can be local, global, or shared with your team.
* requirements.txt - a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project.

```
📦 
├─ .gitignore
├─ README.md
├─ app.py
├─ requirements.txt
├─ static
│  ├─ new_code.png
│  ├─ qrcode.jpg
│  └─ style.css
└─ templates
   ├─ bar.html
   ├─ index.html
   └─ result.html
```

## How to install and run the Application.

Clone this repository:
```
git clone https://github.com/SubramanyaKS/QRCodeGenerator.git
```

Then install python flask and all requirements:
```
pip install -r requirements.txt
```
Run the development web server:
```
python app.py
```
Open the URL http://localhost:5000/ to access the application.


## Demo

<img src="" alt="demo"/>


## Credits / References:
* Github
* Towardsdatascience
* GeeksforGeeks
* [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)

If you like this project fork this project and ⭐ this repository.
Thank You have a good day.

