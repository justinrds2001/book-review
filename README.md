# Book Review App

## Overview

This is a simple Book Review application built as part of a Udemy course.

## Tech Stack

- **Laravel** - Main framework for backend and business logic
- **Docker Compose** - Containerized development environment
- **Tailwind CSS** - Styling and layout

## Installation

### Prerequisites

- Docker & Docker Compose for database & db client
- PHP ^8.2 installed on your machine (or with docker)
- Composer installed on your machine (or with docker)

### Steps

1. Clone this repository:
   ```sh
   git clone git@github.com:{github_username}/book-review.git
   cd book-review
   ```
2. Copy the environment file:
   ```sh
   cp .env.example .env
   ```
3. Start the database server using Docker Compose:
   ```sh
   docker-compose up -d
   ```
4. Run Laravel migrations and seed database (if needed):
   ```sh
   php artisan migrate --seed
   ```

## Usage

- View books and their reviews
- Query books by title
- Query books by popularity and rating

## Development

To start a development environment:

```sh
   php artisan serve
```
