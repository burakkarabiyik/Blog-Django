# Blog-Django



## Set Up


`$ pip install -r requirements.txt`

`$ py manage.py makemigrations blog blogadmin`

`$ py manage.py migrate`

`$  py .\manage.py createsuperuser`

`$ py manage.py runserver`

> http://localhost:8000/login/

+ Live -> https://django-blog-brk.herokuapp.com/
## Database sqlite

+ MyCategories
    + categoryname
+ Users
    + username
    + password
    + ad
    + soyad
    + yas
    + is_admin
    + is_yazar
+ Posts
    * user
    * title
    * content
    * publishing_date
    * image
    * slug
    * status


## Pages

+ /
    + index
    + about
    + contact
    + _post
    + login
    + register
+ /admin/
    + admin/articles/
    + admin/accounts/
    + admin/add/
    + admin/addcategory/


### Templatesfrom templatemo.com

## Screenshots

![](https://raw.githubusercontent.com/burakkarabiyik/Blog-Django/main/screenshots/index.png)

> Index Page

![](https://raw.githubusercontent.com/burakkarabiyik/Blog-Django/main/screenshots/login.png)

> Login Page

![](https://raw.githubusercontent.com/burakkarabiyik/Blog-Django/main/screenshots/register.png)

> Register Page

![](https://raw.githubusercontent.com/burakkarabiyik/Blog-Django/main/screenshots/dashboard.png)

> Dashboard Page