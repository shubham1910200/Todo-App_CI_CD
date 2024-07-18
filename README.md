# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/shubham1910200/Todo-App_CI_CD.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)

```bash
pip freeze> requirement.txt
- Purpose: pip freeze lists all installed Python packages and their versions. It's particularly useful when you want to document or replicate the exact environment where your Python project runs.

```
=======

## requirements

```nohup python3 manage.py runserver 0.0.0.0:8000 &
ssh -i "~/project1.pem" ubuntu@ec2-44-201-201-120.compute-1.amazonaws.com
source myenv/bin/activate```

```
# Step-by-Step Installation of Django

### 1. Update your package list:
```bash
 sudo apt update
```
### 2. Install Python and pip:
Ensure you have Python and pip installed. If not, install them using:
```bash
sudo apt install python3 python3-pip

```
### 3. Create a virtual environment (optional but recommended):
Creating a virtual environment is a good practice to manage dependencies for your project.
```bash
python3 -m venv myenv
source myenv/bin/activate


```
### 4. Install Django using pip:
Once the virtual environment is activated (if you're using one), you can install Django:
```bash
pip install django

```
### 5. Verify the installation:
Check the installed version of Django to confirm the installation:
```bash
python -m django --version

```
```bash
lsof -i:8000
```

- Created CI/CD pipeline of webapp using docker,jenkins and aws




# Install Jenkins
```bash
sudo apt update
sudo apt install openjdk-11-jre
java -version
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
/usr/share/keyrings/jenkins-keyring.asc > /dev/null

sudo apt update
sudo apt install jenkins

sudo systemctl enable jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins
```
## Install jenkins using docker
```bash
sudo docker pull jenkins/jenkins
sudo docker run -d -p 8080:8080 docker.io/jenkins/jenkins:latest
```


