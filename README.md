# ECOMMERCE
- This Project focuses on new era shopping alternative i.e offline and online Shopping both options in single interface. Here Online shopping is as usual like other ecommerce site but offline shopping includes slot booking module integrated . Actually Online shopping section and slot booking independent modules are integrated in one ecommerce site.  
## FUNCTIONS

## Customer

### Admin

### Other Features



## RUNNING THIS PROJECT
- Install Python(3.7.6) and add it to the path
- Run following in terminal:
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf

```
### DOWNLOADING THE PROJECT
- Download The Zip Folder and Extract it
- Move to project folder in Terminal and run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Then enter following URL in browser:
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED IN CONTACT US PAGE
- In settings.py file make following changes
```
HOST_EMAIL= 'youremail@gmail.com'
HOST_EMAIL_PASSWORD = 'password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps

