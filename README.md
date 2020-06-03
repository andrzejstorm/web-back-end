# Reasonable Productivity Back-end

This is an api for the Reasonable Productivity system built with the Django REST Framework.

## Running Locally

1. Clone this repo
1. cd into this repo
1. Create a python virtual environment: `python -m venv venv`
1. Activate virutal environment: `source venv/bin/activate`
1. `pip install -r requirements.txt`
1. `python manage.py runserver`

## Schema

**Task**

* title
* description
* created_at
* updated_at

**User**

* email (unique, used for login)
* password

**UserProfile**

* first_name
* last_name
* image
* fb_profile
* twitter_profile
* linkedin_profile
* website
