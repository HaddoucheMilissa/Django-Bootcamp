# Django-Bootcamp

## Introduction

This document provides instructions for setting up and running the project.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Python](https://www.python.org/downloads/) (version 3.12.4 or later)
- [pip](https://pip.pypa.io/en/stable/) (Python package installer)

## Installation

Follow these steps to set up and run the Django project.

## 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

## 2. Create and Activate a Virtual Environment

It is recommended to use a virtual environment to manage project dependencies

```bash
python -m venv venv
```

**On Windows:**

```bash
venv\Scripts\activate
```

**On macOS & Linus:**
```bash
source venv/bin/activate
```
## 3. Install Dependencies
```bash
pip install django
```
**verification**
```bash
python -m django --version
```
## 3. Create a Django Project
```bash
python -m django startproject django_bootcamp
```
This will create a new directory called django_bootcamp with the following structure:

```markdown
django_bootcamp/
    manage.py
    django_bootcamp/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```
Then
```bash
cd Django_Bootcamp
python manage.py runserver
```
