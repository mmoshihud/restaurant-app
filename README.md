# Django REST Framework App

[![Build Status](https://travis-ci.org/username/repo.svg?branch=master)](https://travis-ci.org/username/repo)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

This is a Django app built with Django REST Framework. It provides a RESTful API for managing restaurant data.

## Features

- API endpoints for CRUD operations on restaurants, menus, and orders
- Authentication and authorization using JWT tokens
- Pagination and filtering options for API responses
- Unit tests for all API endpoints

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/mmoshihud/restaurant-app.git
   ```

2. Install the dependencies:

   ```shell
   pip install -r requirements.txt
   ```

3. Set up the database:

   ```shell
   python manage.py migrate
   ```

4. Start the development server:

   ```shell
   python manage.py runserver
   ```

## Usage

To access the API endpoints, use the following base URL:
