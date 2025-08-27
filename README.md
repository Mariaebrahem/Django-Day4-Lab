Django Day 4 - Lab Notes

This repository contains practice notes and examples from *Day 4* of learning Django as part of the Full Stack Web Development with Python track at ITI.

## 📌 Topics Covered
- *Django Admin Customization*
  - Changing object display names with __str__()
  - Using Meta class for model options (ordering, etc.)

- *Django Models Fields*
  - Field types: CharField, IntegerField, DateField, DateTimeField, etc.
  - Field options: blank, verbose_name, choices, help_text
  - Handling Date & Time fields (DateField, TimeField, DateTimeField)

- *Migrations & Admin*
  - Running migrations:  
    bash
    python manage.py makemigrations
    python manage.py migrate
    
  - Registering models in admin.py

- *QuerySets & ORM*
  - Filtering data with get(), filter(), exclude()
  - Ordering results
  - Lookup expressions: exact, contains, in, range

- *Media Files in Django*
  - Configuring settings.py and urls.py
  - Uploading and serving user media files
  - Embedding images in templates

## 🛠 Requirements
- Python 3.10+
- Django 5.0+
- Virtual Environment recommended

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/YourUsername/Django-Day4-Lab.git
