# 🐛 Mini Issue Tracker (Laravel 11)

A simple **Issue Tracking System** built with **Laravel 11** + **Blade + AJAX**, where a team can manage projects, issues, tags, and comments.  
This project was developed as a **technical task**

---

## 🔎 Overview

**issue-tracker** is a powerful developer tool designed to streamline the development, testing, and deployment of Laravel applications.  
It integrates essential workflows, ensuring consistency and efficiency across the project lifecycle.

### Why issue-tracker?
This project simplifies setup processes and automates routine tasks, enabling developers to focus on building features.  

The core features include:
- ⚡ **Laravel Integration**: Seamlessly connects with Laravel’s framework, artisan CLI, and dependencies.
- ✅ **Testing Configuration**: Uses phpunit.xml to ensure comprehensive test coverage and environment consistency.
- 🎨 **Frontend Asset Management**: Leverages vite.config.js and package.json for efficient asset compilation and hot module replacement.
- 🔄 **Streamlined Workflows**: Automates build, test, and deployment, reducing overhead and minimizing errors.
- 🌍 **Environment Consistency**: Manages dependencies/configurations to maintain uniform environments across dev, test, and production.

---

## ✨ Features

### Core
- **Projects**: Create, edit, delete, list, and show projects (with their issues).
- **Issues**: Create, edit, delete, list with filters (status, priority, tag).
- **Tags**: Create tags, attach/detach to issues via AJAX.
- **Comments**: Load/add comments dynamically via AJAX.

### Bonus
- 👥 Assign multiple users to issues.
- 🔐 Authorization policies for project ownership.
- 🔎 Search issues with AJAX debounce.

---

## 🛠️ Tech Stack
- Laravel 11  
- MySQL  
- Blade Templates  
- Bootstrap 5  
- AJAX / Fetch API  

---

## 🚀 Installation

```bash
git clone https://github.com/YOUR_USERNAME/issue-tracker.git
cd issue-tracker
composer install
npm install && npm run dev
cp .env.example .env
php artisan migrate --seed
php artisan serve
