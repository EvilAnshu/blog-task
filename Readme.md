<!-- ============================================ -->
**Complete Mern**
<!-- Authentication Api -->

<!-- Register -->
method = "POST"
http://localhost:5000/api/auth/register

// Register New User Api Data
{
    "email":"ab@gmail.com",
    "password":"anshu1",
    "name":"Anshu Verma",
    "role":"admin"
}

<!-- Login -->
method = "POST"
http://localhost:5000/api/auth/login

// Login Api Data
{
    "email":"a@gmail.com",
    "password":"verma1"
}

<!-- Change Password -->
method = "PUT"
http://localhost:5000/api/auth/change-password

// Change Password  Api Data
{
    "currentPassword":"verma1",
    "newPassword":"verma1"
}

<!-- Logout -->
method = "GET"
http://localhost:5000/api/auth/logout



<!-- ============================================ -->

<!-- Categories Api -->

<!-- Get Categories -->
method = "GET"
http://localhost:5000/api/categories/


<!-- Add Category -->
method = "POST"
http://localhost:5000/api/categories/

// Add New Category Api Data
{
    "category_name": "Clothes",
    "meta_title": "Clothes",
    "meta_description": "Information about all type of clothes avilable here",
    "meta_keywords": "jens, pants, t-shirt"
}

<!-- Edit Category -->
method = "PUT"
http://localhost:5000/api/categories/647188eb2c351169582d1e56

// Edit Category Api Data
{
    "category_name": "Clothes",
    "meta_title": "Clothes In India",
    "meta_description": "Information about all type of clothes avilable here",
    "meta_keywords": "jens, pants, t-shirt"
}


<!-- ============================================ -->

<!-- Posts Api -->

<!-- Get Posts -->
method = "GET"
http://localhost:5000/api/posts/

<!-- Add Post -->
method = "POST"
http://localhost:5000/api/posts/

// Add New Post Api Data
{
    "post_title": "Pants",
    "post_content": "Very nessesary",
    "category_id": "647188eb2c351169582d1e56"
}

<!-- Edit Post -->
method = "PUT"
http://localhost:5000/api/posts/64719607775e705d1f57ae16

// Edit Post Api Data
{
    "post_title": "Pants Updated",
    "post_content": "Very nessesary",
    "category_id": "647188eb2c351169582d1e56"
} 


<!-- ============================================ -->
