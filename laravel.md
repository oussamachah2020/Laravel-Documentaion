# ---------------Laravel Note-------------------

> artisan file is the responsible for the server => to run the app `php artisan serve`
> the `blade` extension in file represent the template engine

**Laravel use MVC: **

```
- MODEL -> data
- VIEW -> interface
- CONTROLLER -> connection
```

#Routing:
> Routing => giving the path to where data will sent and displayed

```````
#### 1. Routes
> in laravel, we use the `Route` class which contains a `get()` method that takes two parameters 1-> the path & 2 -> a function with specific task.

#### 2. Routes Requests
> assign a parameter to the url route in order to filter or get a specific data
**Syntax** => urlPath/?{parameter_name}="value_wanted"

#### 3. Routing Categories
> instead of passing an argument value with `Routes Request`, you can get the same results using `Routing Categories` using `{}` after the route path
**Syntax => `Route::get('/urlPath/{category}', function($category_variable) {
    return $category_variable
  })`
```

``````
#Controllers:
> Controller => 
