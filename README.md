# Hotel V Layout

A front-end layout project for a hotel website, built as part of a WorldSkills practice exercise. The page showcases a full hotel detail view including room booking, meeting & events, a photo gallery, testimonials, and a "Things To Do" sidebar — all structured with a responsive, multi-column layout.

## Features

- **Room Booking Widget** – Allows guests to enter arrival/departure dates, number of nights, adults, and children to check availability.
- **Side Navigation** – Vertical hotel navigation with links to Find a Hotel, Meeting & Events, and About Hotel.
- **Hotel Detail Sub-navbar** – Displays amenities, map, and room type options, along with check-in/check-out times and a map image.
- **Meeting & Events Section** – Showcases event venue types (Gatherings, Meetings, Workshops) with images.
- **Photo Gallery** – Canvas-based photo gallery with supporting hotel imagery and guest testimonials.
- **Things To Do Sidebar** – Promotional ads sidebar with a sponsor callout.
- **Footer** – Contact info, newsletter subscription, and hotel group branding.

## Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, layout (multi-column/grid), and responsive design |
| **JavaScript** | Photo gallery canvas rendering (`photo-gallery.js`) |
| **PHP** | Server-side icon include (`icon.php`) |
| **prefix-free.js** | CSS vendor prefix automation |
| **Custom Fonts** | Local font assets (via `Fonts/` directory) |

## Project Structure

```
hotel-v-layout/
├── index.html          # Main HTML page
├── style.css           # All styles for the layout
├── Fonts/              # Custom font files
├── Images/             # Image assets (photos, map, icons, ads)
└── js/
    ├── photo-gallery.js  # Canvas-based photo gallery script
    └── prefix-free.js    # CSS prefix library
```

## Credits

© 2015 WorldSkills
