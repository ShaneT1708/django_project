[![Build Status](https://travis-ci.org/ShaneT1708/django_project.svg?branch=master)](https://travis-ci.org/ShaneT1708/django_project)


# Shane's Musical Artifacts

A website marketplace for Musical Antiques and oddities 
 
## UX
 
The UX  was a big priority for me in this project. I made sure present everything in a clean and visually appealling way. In order to achieve this, I started out with a bootstrap theme(https://startbootstrap.com/themes/grayscale/), and customised it to fit my requirements.
I decided on a colour scheme of warm orange and brown hues, which I felt conveyed the vintage theme of the website idea. I made sure that all of my product images fit with this visual aesthetic .

The user is able to add items to a cart, and go to a checkout page if they are registered and signed in. Infastructure for payment is set up using Stripe.

## Features

As my time for this project was limited, the website is limited to core features. These allow the user to:
- Register and Sign in
- Browse items for sale and add them to a cart
- Checkout and make payments using Stripe
- Subscribe to a news letter and get in contact 

### Features Left to Implement
- Editable profile details
- Allow user comments
- Allow items to be bid on
- Automatically updating product list

## Technologies Used

- HTML: Used to structore webpages
- CSS: Used for styling
- Bootstrap: Needed for use of a Bootstrap theme, which was used as a base for styling
- Python: Used for logic between webpages
- Django: Framework used for the whole website
- Stripe: Used to to handle the E-commerce side
- Travis: For help with testing
- Github: Used for version control
- Heroku: Used for hosting



## Testing

Testing was done through a combination of manual testing and using Travis.
Travis was used to diagnose technical problems, such as installed packages conflicting with each other.
Care was taken to make sure that all of the features work as intendid. I tested every page on a variety of screen sizes to make sure everthing looked good.
I ensured that the website looked and functioned the same on Heroku as it did locally.

## Deployment

The source code can be accessed at https://github.com/ShaneT1708/django_project.
Heroku was used for live deployment. It can be accessed here: https://django-project-st.herokuapp.com/

## Credits

Grayscale Bootstrap theme from Startbootstrap. https://startbootstrap.com/themes/grayscale/
Images used were obtained with Google Images
