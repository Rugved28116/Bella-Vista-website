# Bella Vista Restaurant Website

A restaurant website for Bella Vista - an Italian restaurant. This website was created as a college assignment project.

## What is this project?

This is a website for a restaurant called Bella Vista. It includes pages to show the menu, information about the restaurant, and a form where people can make reservations.

## Pages included

- `index.html` - Home page with hero section and testimonials
- `menu.html` - Shows the menu with all dishes
- `about.html` - Information about the restaurant
- `contact.html` - Reservations form and contact information

## Technology used

- HTML5 - Main structure of pages
- CSS3 - Styling and colors
- JavaScript - Making the menu work and form submission
- Font Awesome - Icons
- Google Fonts - Nice looking fonts

## Styling

The website uses:
- Dark red (#8b0000) as the main color
- White and light beige backgrounds
- Playfair Display font for headings (elegant look)
- Inter font for regular text

## Features

### What works:
- Mobile responsive (works on phone, tablet, desktop)
- Navigation menu that appears on smaller screens
- Reservation form to book a table
- Different sections for menu items
- Customer testimonials displayed
- Newsletter signup

### How the form works:
When someone fills out the reservation form and clicks submit:
1. The form sends the data to the backend
2. Backend receives it and saves to a file
3. User sees a confirmation message

## How to use

1. Open the HTML files in a browser
2. Or run a local server like:
   ```
   python -m http.server 8000
   ```

## Backend

The backend files are in a separate folder (`bella-vista-backend`). It has:
- A PHP server that handles reservations
- Files stored as JSON (data/reservations.json)
- Email confirmations (saved as text files in outbox folder)

To run backend:
```
php -S localhost:5000 server.php
```

## What was hard

- Making the design look good on all screen sizes
- Getting the mobile menu to slide in smoothly
- Handling form submission and showing success/error messages
- Understanding how to connect frontend to backend

## Things I'd like to improve

- Actually sending emails instead of saving to files
- Using a real database
- Adding more pages
- Better error handling
- Admin panel to view reservations

## Credits

- Images are from Unsplash
- Icons from Font Awesome
- Fonts from Google Fonts

Made by: Nidhi  
Date: March 2026
  
