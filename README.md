# Laravel Social Authentication with OAuth using Laravel Socialite

## Project Overview

This Laravel project demonstrates the implementation of social authentication using Laravel Socialite. The focus is on integrating GitHub and Twitter authentication to provide users with the convenience of logging in using these platforms.

## Tech Stack

### Backend (Laravel)

-   Laravel 10.10
-   Laravel Sanctum 3.2
-   Laravel Socialite 5.8
-   Guzzle HTTP 7.2
-   Laravel Breeze 1.23
-   Laravel Tinker 2.8
-   Laravel Pint 1.0
-   Laravel Sail 1.18
-   PHPUnit 10.1
-   Spatie Laravel Ignition 2.0

### Frontend (Vite + Tailwind CSS)

-   Vite 4.0.0
-   Tailwind CSS 3.1.0
-   Alpine.js 3.4.2
-   Axios 1.1.2
-   Laravel Vite Plugin 0.8.0
-   Autoprefixer 10.4.2
-   PostCSS 8.4.6
-   Tailwind CSS Forms 0.5.2

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/aldiandarwin/OAuth-using-Laravel-Socialite.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd your-social-auth-project
    ```

3. **Install PHP dependencies using Composer:**

    ```bash
    composer install
    ```

4. **Install NPM dependencies:**

    ```bash
    npm install
    ```

5. **Copy the `.env.example` file and rename it to `.env`. Update the database configuration and other necessary settings:**

    ```bash
    cp .env.example .env
    ```

6. **Generate an application key:**

    ```bash
    php artisan key:generate
    ```

7. **Migrate the database:**

    ```bash
    php artisan migrate
    ```

8. **Start the development server:**

    ```bash
    php artisan serve
    ```

9. **Build the frontend assets:**

    ```bash
    npm run dev
    ```

## Social Authentication

This project showcases social authentication with GitHub and Twitter. Users can log in using their GitHub or Twitter accounts, providing a seamless and user-friendly authentication experience.

## OAuth Configuration

Configure your OAuth credentials in the `.env` file:

```dotenv
GITHUB_CLIENT_ID=your-github-client-id
GITHUB_CLIENT_SECRET=your-github-client-secret
GITHUB_REDIRECT_URI=http://your-app-url/github/callback

TWITTER_CLIENT_ID=your-twitter-client-id
TWITTER_CLIENT_SECRET=your-twitter-client-secret
TWITTER_REDIRECT_URI=http://your-app-url/twitter/callback
```
