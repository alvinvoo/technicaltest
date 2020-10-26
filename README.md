# Technical Test 
## - for backend developer position at Liv3ly

1. Create a github repo named: technicaltest_for_liv3ly_interview
2. Using the latest <strong>Laravel</strong> version and <strong>TDD</strong> practise, create a REST API with following acceptance criteria:  
   a. A user should be able to register  
   b. A user should be able to login  
   c. A user should be able to logout  
   d. A user should be able to create user profile  
   e. A user should be able to view user profiles (including others profile)  
   e. A user should be able to edit <strong>ONLY</strong> his/her own user profile (user A cannot edit user B profile)  
3. Tips: Using TDD practice <i>(red-green test)</i>, first write the test cases based on the above acceptance criteria before writing the implementation.
4. Tips: Below are the suggested endpoints naming (you can name it differently if you want to):  
   a. POST /register  
   b. POST /login  
   c. DEL /logout  
   d. POST /users/create  
   e. GET /users/{user_id}  
   f. PATCH /users/{user_id} - remember, a user can only change his/her own profile  
5. Tips: For authentication, you can checkout [Laravel Passport](https://laravel.com/docs/8.x/passport)
6. Tips: For TDD, you can checkout this Laracast [TDD for laravel](https://laracasts.com/series/build-a-laravel-app-with-tdd)
