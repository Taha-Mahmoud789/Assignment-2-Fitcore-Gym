# FitCore Gym Landing Page

A modern **Gym Landing Page** built using **HTML5 and CSS3**. This
project demonstrates how to build a structured landing page using
**float and inline-block layout techniques** without using any
frameworks.

------------------------------------------------------------------------

## Project Preview

Main sections included:

-   Hero Section
-   Features Section
-   More Than Just a Gym Section
-   Testimonials Section
-   Stats Section
-   Membership Form
-   Footer

------------------------------------------------------------------------

## Hero Section

**Purpose:**\
The first visible area of the page introducing the gym and encouraging
users to start their fitness journey.

**Contains** - Main heading - Description - Call-to-action buttons -
Hero image

**Layout Technique** - `display: inline-block`

------------------------------------------------------------------------

## Features Section (Why Choose Us)

Highlights the main advantages of the gym.

**Feature Cards** - Premium Equipment - Expert Trainers - Flexible Hours

Each card includes: - Icon - Title - Description

Layout uses: - `display: inline-block`

------------------------------------------------------------------------

## More Than Just a Gym Section

Shows additional services offered by the gym.

**Services** - Group Classes - Nutrition Guidance - Recovery Zone

Layout: - Left side → image - Right side → services

CSS technique: - `float: left` - `float: right`

------------------------------------------------------------------------

## Testimonials Section

Displays feedback from gym members to build trust.

**Members** - David Martinez - Mike Chen - James Rodriguez

Each testimonial includes: - Avatar - Name - Result - Review text

Layout: - `float: left`

------------------------------------------------------------------------

## Stats Section

Shows key statistics about the gym.

-   2500+ Active Members
-   15+ Expert Trainers
-   50+ Group Classes
-   24/7 Access Hours

Layout: - `width: 25%` - `float: left`

------------------------------------------------------------------------

## Membership Form

Allows users to join the gym.

**Form Fields** - First Name - Last Name - Email Address - Phone
Number - Membership Type - Fitness Goals

Best practices: - `name` attribute for inputs - `id` attribute for
inputs - `label` connected using `for` - `type="tel"` for phone number

Example:

``` html
<label for="email">Email Address</label>
<input type="email" id="email" name="email">
```

------------------------------------------------------------------------

## Footer Section

Provides navigation and contact information.

Columns: 1. About FitCore 2. Quick Links 3. Contact Info

Social Links: - Facebook - Instagram - Twitter

Layout: - `float`

------------------------------------------------------------------------

## Footer Bottom

Contains:

-   Copyright
-   Privacy Policy
-   Terms of Service
-   Cookie Policy

Layout:

-   Left side → copyright
-   Right side → links

------------------------------------------------------------------------

## CSS Techniques Used

-   Float
-   Inline-block
-   Clearfix

Clearfix example:

``` css
.clearfix::after {
  content: "";
  display: block;
  clear: both;
}
```

------------------------------------------------------------------------

## Project Structure

    FitCore-Gym
    │
    ├── index.html
    ├── README.md
    │
    ├── css
    │   └── styles.css
    │
    └── images
        ├── hero-section-img.png
        ├── why-choose-us.png
        ├── avatar-1.jpg
        ├── avatar-2.jpg
        └── avatar-3.jpg

------------------------------------------------------------------------

## Technologies Used

-   HTML5
-   CSS3

No frameworks were used.

------------------------------------------------------------------------

## Author

Developed by **Taha Mahmoud**
