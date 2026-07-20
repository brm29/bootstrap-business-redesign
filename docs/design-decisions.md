# Design Decisions: AllyCats Hair Studio Redesign

## Framework
HTML, CSS and Bootstrap.

## Layout choices
- Used Bootstrap's grid system for responsive sections that can  stack on mobile
- Replaced the old navigation links with a Bootstrap navbar that automatically collapses into a menu on smaller screens, while still letting users jump to different sections of the page.
- Added more clear call-to-action buttons throughout the website to make it easier for users to book a service or get in touch without having to search for the right link.


## Components used
- Navbar (responsive, collapsible)
- Cards (services / gallery and other sections)
- Bootstrap Icons (service icons instead of generic imagery)
- Forms (contact/newsletter section)
- Footer with grid-based link columns and newsletter signup

## Custom CSS / branding
- Brand color set in `css/styles.css`, applied over Bootstrap's default primary color across buttons, icons, and highlights.
- Spacing to make the website look cleaner and more professional instead of like a basic template.
- Improved the buttons by adding custom colours, hover effects, and subtle animations.
- Added smooth hover effects to images and cards to make the website feel more interactive.


## What this improves on vs. the original

| Original issue | Our improvement |
|---|---|
| Generic design | Used a consistent red colour theme and custom styling to give the website its own identity. |
| Basic navigation | Replaced it with a responsive Bootstrap navbar that is easier to use on both desktop and mobile. |
| Important actions were difficult to find | Added multiple clear call-to-action buttons throughout the website to encourage bookings and enquiries. |
| Limited visual feedback | Added hover effects and animations to buttons, cards and gallery images for a more interactive experience. |
| Uneven spacing and layout | Improved spacing and typography to create a cleaner, more balanced design. |
| Gallery looked plain | Redesigned the gallery with consistent image sizes, hover zoom effects and text overlays. |
| Mobile experience could be improved | Used Bootstrap's responsive grid and components to make sure the website works well across different screen sizes. |

