## Start Using Pipenv

``` bash
# Activate virtualenv
$ pipenv shell

# Install dependencies
$ pipenv install

# Create DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhost:5000)
python app.py
```

## Routes

* GET     /product/:id
* GET     /showallproducts/:id
* POST    /addproduct
* PUT     /updateproduct/:id
* DELETE  /deleteproductbyid/:id
