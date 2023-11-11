<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<h1 align="center"> Assignment - Laravel Structure and Artisan Commands </h1> <br> <bar></bar>

> Step 1. Create a new Laravel application using the command line. Use the necessary Laravel installer command to create the project.
```
composer create-project laravel/laravel ostad-app   
```

> Step 2. Navigate into the project directory (ostad-app)
```
cd ostad-app
```

> Step 3. Once the project is created, use the artisan command to generate a new controller called 'UserController'
```
php artisan make:controller UserController
```

> Step 4. Next, create a route in the web.php file that maps to a function in the UserController. The function should return a simple message like 'Hello, Laravel!'
```
// UserController Function
public function index() {
       return 'Hello, Laravel!';
   }

// import 
use App\Http\Controllers\UserController;

//  Web Routes
Route::get('/', [UserController::class, 'index']);
```

> Step 5. Finally, start the Laravel development server and test the route using a web browser.
```
php artisan serve
```
<h1 align="center"> Thank You ❤️ </h1>
