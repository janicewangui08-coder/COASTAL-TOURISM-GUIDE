# Coastal Tourism Guide

Coastal Tourism Guide is a beginner university programming project about tourism destinations on the Kenyan coast. Visitors can learn about destinations, attractions, activities, and accommodation options through simple web pages.

## Destinations

The website supports these six destination pages:

- Diani
- Kilifi
- Lamu
- Malindi
- Mombasa
- Watamu

Each destination page includes information about the location, main attractions, popular activities, and sample stays. A **Book a Visit** link opens the shared booking page.

## Booking Functionality

The booking form is available on `booking.html`. It collects:

- Full name
- Email address
- Phone number
- Date of visit
- Number of visitors
- Preferred activity

The form checks that the required fields are completed and that the email address has a valid format. JavaScript sends the booking information to Formspree using the `POST` method and `fetch()`. A success or error message is displayed on the page after the submission attempt.

The destination links pass the selected destination to the shared booking form, so the booking information includes the visitor's chosen destination.

## Contact Form

The contact form is available on `contact.html`. It collects the visitor's name, email address, and message. The required fields and email format are checked before JavaScript sends the message to Formspree.

Both booking and contact submissions are handled using Formspree:

`https://formspree.io/f/xwleyavl`

## Technologies Used

- HTML for the website structure and forms
- CSS for layout, colors, buttons, and responsive design
- JavaScript for form validation, submission, and confirmation messages
- Git for tracking project changes
- GitHub for storing and sharing the project repository

## Project Files

The main pages include:

- `index.html` for the home page
- `destinations.html` for the destination list
- `diani.html`, `kilifi.html`, `lamu.html`, `malindi.html`, `mombasa.html`, and `watamu.html` for destination details
- `booking.html` for visit bookings
- `contact.html` for contacting the guide
- `style.css` for the main website styling
