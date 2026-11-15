🎬 Netflix Frontend Clone (HTML5, Tailwind CSS & Vanilla JavaScript)

A fully responsive, feature-rich Netflix web application clone built using pure frontend technologies. This project runs entirely in the browser with mock state management, dynamic UI rendering, and persistent storage via localStorage.

🚀 Key Features & Architecture

1. Multi-View Screen Flow

Landing & Authentication Page: Authentic Netflix landing screen featuring a cinematic backdrop collage, email capture form, FAQ accordion with smooth toggle animations, and a functional Sign In / Sign Up modal.

Profile Selection Screen ("Who's watching?"): Displays multiple avatars (User, Kids, Guest) plus a dynamic Add Profile creator. Selecting the Kids profile automatically applies content maturity filters.

Main Browse Dashboard: The core Netflix streaming experience with sticky navigation, hero banners, and horizontal carousels.

2. Main Dashboard UI Components

Sticky Navigation Bar: Transparent at the top of the page, automatically transitioning to solid black (#141414) on scroll. Includes the Netflix logo, category links (Home, TV Shows, Movies, New & Popular, My List), live search bar, notification dropdown, and profile switcher menu.

Hero Banner Section: Features a highlighted movie or show with gradient vignette overlays, match percentage, release year, maturity rating, duration, synopsis, and interactive Play and More Info buttons.

Horizontal Movie Carousels: At least 5 distinct categories (Trending Now, Netflix Originals, Continue Watching with progress bars, Top Rated Movies, and Action & Adventure) equipped with smooth horizontal scroll buttons.

Interactive Movie Cards: Hovering over any poster card triggers a smooth scale-up transition (scale-112) with quick action buttons (Play, Add/Remove from My List, Like/Rate, and Expand Info).

Movie Details Modal: Clicking "More Info" opens an immersive modal displaying a larger backdrop, cast list, genres, tagging tags, a season/episode breakdown (for TV shows), and a "More Like This" recommendation grid.

My List & Search Filter: Dynamically add or remove titles from your saved list with instant badge counters. Type in the search bar to filter titles instantly across titles, genres, and cast members.

3. Simulated Fullscreen Video Player

Clicking Play on any hero, card, or episode opens an immersive fullscreen video player with:

Animated playback background and center play/pause controls.

Interactive progress bar with click-to-seek functionality.

Skip (+10s / -10s) controls and remaining time counter.

4. Persistence & Tech Stack

Zero Backend: No external server required. All user preferences, likes, saved list items, and profiles are persisted locally via browser localStorage.

Styling: Built with Tailwind CSS via CDN for rapid utility styling, augmented by custom CSS animations and Netflix color palettes (#141414 background, #E50914 Netflix Red).

Typography: Clean, modern sans-serif typography via Google Fonts (Inter).

📂 File Structure

The project is structured as a single, self-contained HTML file for instant portability and previewing:

netflix-clone/
├── index.html        # Complete HTML, Tailwind CSS config, custom styles, and Vanilla JS
└── README.md         # Project documentation and guide


🛠️ Quick Start & Installation

Download or Clone the repository to your local machine.

Ensure you have the index.html file in your project directory.

Open index.html in any modern web browser (Google Chrome, Mozilla Firefox, Apple Safari, or Microsoft Edge) by double-clicking the file or dragging it into your browser window.

No npm installation or build step is required!

💡 Usage Guide

Explore Landing & Demo: Click "Instant Demo" or enter any email address on the landing page to quickly jump into the profile selection and browse dashboard.

Manage Profiles: Switch between profiles or create a new custom profile at any time via the top-right profile dropdown or the profile selection screen.

Save to My List: Click the + button on any movie card to save it to your personal My List view.

Search: Use the top navigation search bar to instantly filter movies and shows by title, genre, or actor.

🛡️ License

This project is created for educational and UI/UX showcase purposes. Netflix and its associated logos are registered trademarks of Netflix, Inc.
