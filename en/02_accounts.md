Accounts
======

Each RamseyX user has an account (project ID) to access the project. 


Fields
------

These fields are all the POST fields used to register an account. Not all
the fields are requried to login.

- username: `[a-zA-Z0-9_]{1,16}`
- password: `[a-zA-Z0-9_]{4,16}`
- email: `[0-9a-z_\\-]+(\\.[0-9a-z_\\-]+)*@([0-9a-z_\\-]+\\.)+[a-z]+`
- recommender: (Same as username)
- computer_name, cpu_brand: See [misc](99_misc.md).

Login
-----

`username` and `password` are posted to `validate_user.php`.

### Return status


Register
-----

All the fields are posted to the server (`sign_up.php`.)

### Return status

