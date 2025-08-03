# README

# Rails 8 Blog Project

A simple blog application built with **Ruby on Rails 8** and **Tailwind CSS**.  
This project was created as a practice app to explore Rails concepts such as:

- RESTful routes
- CRUD functionality (Create, Read, Update, Delete)
- MVC architecture
- Using Tailwind CSS for styling

---
## Demo
You can check out the live version of the blog here: (Please note, that the database is non-persistant) 

[https://blog-project-rails-gmza.onrender.com]

## For local deployment:

## Prerequisites
- Ruby (see `.ruby-version`)
- Bundler (`gem install bundler`)
- SQLite (used for development and test environments; usually included with Rails)


Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mimox98/Blog_project_rails.git
   cd Blog_project_rails

2. ```bash
   bundle install
3. ```bash
   rails db:migrate
4. ```bash
   rails server
5. open the server on your broweser: http://localhost:3000 
---

## Features

- Create, edit, update, and delete articles
- Display a list of all articles
- Simple and clean UI with Tailwind CSS
- Static About page

---

## Tech Stack

- **Ruby**: 3.x
- **Rails**: 8.x
- **Database**: SQLite (development), PostgreSQL (production)
- **CSS**: Tailwind CSS (via `tailwindcss-rails`)

---

