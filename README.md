Hey folks, I have created a job portal site, where companies can register themselves, and after registration ADMIN can approve or reject the company based on their given data. <br>
After getting approved COMPANIES can add jobs to the website for applicants to register.<br>
This website comes with 3 login views, USER, COMPANIES, ADMIN. <be>

>To run this project on your local environment follow these steps :
>
#### Make sure have the latest version of Python is installed in your system by using this command in your terminal
```console
python --version
```

#### The next step to run this project is to install all the packages need for this project by using this command
```console
pip install -r requirements.txt
```

#### After installing all the packages successfully in your environment, Now you have to migrate files to establish your local database 
```console
py manage.py makemigrations
```
```console
py manage.py migrate
```

#### After successful migrations, your project is good to go, To run your project use this command :
```console
py manage.py runserver
```

### The only thing you need to do is create super user for your environment to access the Admin view of this project, use this command to create superuser
```console
py manage.py createsuperuser
```

### Few things you will need to understand about this project

> After the company register themselves in this portal, Company can not login or upload any jobs until the Admin Approve or Accept that Company

## All Set You're good to go !!

![Screenshot (158)](https://github.com/shuvbhamm/Job-Portal-Website-using-Django/assets/108618796/c6d814de-8c79-4eb9-a48e-14d2bb253029)
