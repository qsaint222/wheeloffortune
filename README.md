# Voucher Wheel
Voucher Wheel is a powerful tool to engage your customers by giving them a chance to win a prize by spinning a lucky wheel.

Developed in Python, Django and Javascript, Voucher Wheel is fully customisable in an admin portal.

The wheel was made in Scalable Vector Graphics (SVG) making the website fully responsive and flexible for your needs.

Voucher Wheel can be used as a stand-alone Squeeze Page or Landing Page to capture emails and build a newsletter list. Or as a plugin or popup to your website!

## Project Setup

First you need to set up your virtual environment on the project's root directory

    virtualenv venv
    source venv/bin/activate

Then go to the `wheel` folder and run the following commands

    pip install -r requirements.txt
    python manage.py migrate


### Create admin user

    # python manage.py createsuperuser
    
### Create the static files

    # python manage.py collectstatic

### Load the initial data

    # python manage.py loaddata prizes
