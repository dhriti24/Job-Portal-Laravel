# Job Hunt Project

## Introduction

This project is a job hunting platform developed using PHP and Laravel. It provides a comprehensive set of features to facilitate the job search and application process. Users can register, log in, update account details, change profile photos, change passwords, create, edit, and delete job posts. The home page showcases featured and latest jobs, and users can filter jobs based on keywords, location, category, and experience.

## Table of Contents

-   [Prerequisites](#prerequisites)
-   [Installation](#installation)
-   [Configuration](#configuration)
-   [Usage](#usage)
-   [Features](#features)

## Prerequisites

Make sure you have the following prerequisites installed:

-   PHP
-   Composer
-   Laravel

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/job-hunt.git

    ```

2. **Install Dependencies**

    ```bash
    cd job-hunt
    composer install
    ```

3. **Set up Database**
    ```bash
    php artisan migrate
    ```

## Configuration

    Modify Php.ini file
    ; extension=gd
    extension=gd

## Usage

1. **Run Server**

    ```bash
    php artisan serve
    ```

2. **Open Application**
    ```bash
    http://localhost:8000
    ```

## Features

### User Management:

-   Register
-   Login
-   User Management:
-   Update Account Details
-   Change Profile Photo
-   Change Password

### Job Posting:

-   Create Job Post
-   Edit Job Post
-   Delete Job Post
-   View Job Post Details

### Home Page:

-   Featured Jobs
-   Latest Jobs

### Job Filtering:

-   Keywords
-   Location
-   Category
-   Experience
