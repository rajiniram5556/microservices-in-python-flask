# microservices-in-python-flask
writing the microservices-in-python-flask
1.Installing python 3.x
--https://www.python.org/downloads/macos/ go to this link and download and install 3.x python

2.creating python virtual environments
  follow this tutorial 
    https://docs.python.org/3/tutorial/venv.html

3.installing python vs code extension
  go to extension tab and python extension which is provided by the micro soft

4.sample flask application
 https://flask.palletsprojects.com/en/2.2.x/
 do  
 a.pip install Flask
 b.pip list

 c.then we will create a file in vscode

 Note:before that we have to create .gitignore file to viirtual env filers consideration in vs code
 and open .gitignorefile and write virtual env name like this   tutorial-env

 d.create a folder called src under src create a file app.py as we discussed in step c
 e.run python file

 f.how to create a restfull web application
 go this link https://flask.palletsprojects.com/en/2.2.x/quickstart/#a-minimal-application
 and copy the code

 and if we want to run our flask on diffrerent port we will copy below code

 
if __name__ == '__main__':
      app.run(host='0.0.0.0', port=80)

5.jinja templating for dynamic web pages

 create a folder called templates under templates create index.html
6.using pip to freeze python dependencies
 pip freeze > requirements.txt

 lets some one wants to run our code 
 pio install -r requiremts.txt

7.building the docker image using docker file
install minikube
stae
8.writing docker compose file
9.writing kubernetes mainfest files the application
10.creating helm chart
