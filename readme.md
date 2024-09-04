# How to Set Up the Shopper Laravel Project

Follow these steps to clone the repository, navigate to the project folder, and run the Laravel project.

## Prerequisites

Make sure you have the following installed on your machine:

- **Git**
- **PHP** (version 8.0 or higher)
- **Composer** (PHP package manager)
- **Laravel** (optional, if you want to use the Laravel CLI)

***NOTE***: You need to copy `css` `fonts` and `images` to public folder to render the style and figure.

## Step 1: Clone the Repository

Open your terminal and run the following command to clone the repository:

```bash
git clone https://github.com/nattkorat/natt_korat_hw8.git

```

## Step 2: Navigate to the Shopper Folder

```bash
cd natt_korathw8/shopping

```

## Step 3: Install Dependencies

```bash
composer install
```

## Step 4: Set Up the Environment

```bash
cp .env.example .env
```

## Generate the application key:
```bash
php artisan key:generate
```

## Step 5: Run the Laravel Project
```bash
php artisan serve
```

### Happy coding!
