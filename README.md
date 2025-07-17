# Insurance Management
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Shubham%20Patil-red)
---
## screenshots
### Homepage
![homepage snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/homepage1.png)
### Admin Dashboard
![dashboard snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/admin_dashboard.png)
### List Policy 
![policy snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/policy.png)
### View Policy 
![policy snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/view_policy_holder.png)
### View Customer
![customer snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/view_customer.png)
### Customer Dashboard
![dashboard snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/customer_dashboard.png)
### Customer History
![dashboard snap](https://github.com/shubhampatil-d/Insurance-Management-System/blob/main/static/image/customer_history.png)
---
## Functions
### Admin
- Admin account can be created using createsuperuser command.
- After login, admin can view/update/delete customer
- Can view/add/update/delete policy category like Life, Health, Motor, Travel
- Can view/add/update/delete policy
- Can view total policy holder, approved policy holder, disapproved policy holder
- Can approve policy, applied by customer
- Can answer customer question

### Customer
- Create account (no approval required by admin)
- After login, can view all policy that are added by admin.
- If customer likes any policy, then they can apply for it.
- When customer will apply for any policy, it will go into pending status, admin can approve it.
- Customer can check status of his policy under history section
- Customer can ask question from admin. 

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements.txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps
```


## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Gmail](Shubhampatil21199@gmail.com)
- [Visit my LinkedIn](https://www.linkedin.com/in/shubham-patil-89356a340/)

## You create an admin user with the command:
-python manage.py createsuperuser
-Qwerty123