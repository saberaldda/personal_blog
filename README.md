<a href="https://github.com/saberaldda/Personal_blog"> <h1 align="center">Personal Blog</h1></a>

## About

a personal blog with laravel-ui.

#
## Table of Contents

* [Screenshots](#screenshots)
* [Requirements](#requirements)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)

<a name="screenshots"></a>
## Screens

![Screens](https://raw.githubusercontent.com/saberaldda/Personal_blog/main/storage/mockups/6_screeens_mockup.png)


<a name="requirements"></a>
## Requirements

Package | Version
--- | ---
[Composer](https://getcomposer.org/) | V2.1.12+
[Php](https://www.php.net/)          | V4.4+
[Node](https://nodejs.org/en/)       | v18.12.0+
[Npm](https://nodejs.org/en/)        | V9.1.2+ 

<a name="dependencies"></a>
## dependencies

Package | Version
---- | ----
[laravel/ui](https://github.com/laravel/ui) | ^3.3

<a name="installation"></a>
## Installation

> **Warning**
> Make sure to follow the requirements first.

Here is how you can run the project locally:
1. Clone this repo
    ```sh
    git clone https://github.com/saberaldda/Personal_blog.git
    ```

1. Go into the project root directory
    ```sh
    cd Personal_blog
    ```

1. Copy .env.example file to .env file
    ```sh
    cp .env.example .env
    ```
1. Create database `blog` (you can change database name)

1. Go to `.env` file 
    - set database credentials 
        ```sh 
        DB_DATABASE=blog
        DB_USERNAME=root
        DB_PASSWORD=[YOUR PASSWORD]
        ```
    > Make sure to follow your database username and password

1. Install PHP dependencies 
    ```sh
    composer update
    ```

1. Generate key 
    ```sh
    php artisan key:generate
    ```

1. install front-end dependencies
    ```sh
    npm install && npm run dev
    ```

1. Run migration
    ```
    php artisan migrate
    ```
    
1. Run seeder
    ```
    php artisan db:seed
    ```
    this command will create users (admin):
     > email: admin@admin.com , password: password


1. Run server 
   
    ```sh
    php artisan serve
    ```  

1. Visit [localhost:8000](http://localhost:8000) in your favorite browser.

<a name="contributing"></a>
## Contributing
    > Pull requests are welcome.
