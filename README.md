# reet.org / bloodlluxe

This is an ongoing experiment for rediscovering personal expression on the Internet, inspired by my own design. I tried my best to add an indie design and cool features, and I'll keep updating it in the future.

## Built with
- Markup & Styling: Vanilla HTML5 & CSS3 (clean, zero bulky front-end frameworks).
- Backend & Database: Supabase (PostgreSQL) with Row-Level Security (RLS) to keep visitor messages private.
- Hosting: Neocities (Static site hosting).

## Project Structure
├── index.html       # Main landing page & layout

├── style.css        # Custom styles, responsive tweaks & themes

├── banner7.jpg      # Header illustration / banner art

└── README.md        # You are here!

## How the Message Box works
The contact section uses Supabase's JS SDK loaded via CDN. Submissions push directly to an anon-insertable messages table protected by PostgreSQL Row Level Security:

- Anyone visiting the site can write to the table.

- Only I can read the submissions via the authenticated Supabase admin dashboard, keeping everyone's messages safe and spam-free

## Support and Connect
- Live site: reett.neocities.org
- Neocities profile: <a href="[https://github.com](https://neocities.org/site/reett)" target="_blank">bloodlluxe</a>

Thank you for stopping by. Have fun!
