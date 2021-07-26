# Blog-Django



## Set Up


`$ pip install -r requirements.txt`

`$ py manage.py makemigrations`

`$ py manage.py migrate`

`$  py .\manage.py createsuperuser`

`$ py manage.py runserver`

> http://localhost:8000/login/

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