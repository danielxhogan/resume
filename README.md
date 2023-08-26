# Daniel Hogan

danielxhogan@gmail.com | linkedin.com/in/danielxhogan | github.com/danielxhogan | danielhoganofficial.com | 541-761-3824 | Central Point, OR 97502 | US Citizen

## Education

### Southern Oregon University | Ashland, OR

#### Bachelor of Science in Computer Science

_March 2020 – June 2023_

## Projects

### Movieshlok

_From kino to schlock, and everything in between_

website - movieshlok.com \
Github: github.com/danielxhogan/movieshlok \
Demo: youtube.com/watch?v=5nCuNbf1WWw

<ins>Overview</ins> \
Movieshlok is a website that lets users search for and view details about movies and cast & crew members. They can create accounts and leave reviews of movies, or just read and comment on reviews left by other users. They can view a list of all their own or other users' reviews. They can like and rate movies on a 5 star rating scale. They can also add movies to their watchlist and view all movies on their own or other users' lists.

- Developed an interactive UI that conditionally renders based on users login status, updates when a user creates or deletes new posts, and is fully responsive
- Built an authentication system that generates auth tokens on login, checks authentication at every level (UI rendering, event handlers, api endpoints), and prevents unauthorized behavior
- Established websocket connections between server and client for real time communication in review and comment sections
- Engineered an LRU (Least Recently Used) caching layer for the api using Redis
- Dockerized the entire app so the website can be deployed with one command

Tech used: Typescript, HTML, CSS, React, Redux toolkit, Next, ChakraUI, Rust, Warp, JWT, Bcrypt, Diesel, PostgreSQL, Redis, TMDB api, Docker, DigitalOcean

### MVPlaylist

_Turn your Spotify playlist into a Youtube music video playlist_

website - mvplaylist.vercel.app \
Github: github.com/danielxhogan/mvplaylist \
Demo: youtube.com/watch?v=70tjwO3O_Q4

<ins>Overview</ins> \
MVPlaylist is a website that allows users to log in to their existing Spotify account. It lets them view their playlists and play songs in the browser. They can also search Youtube for videos related to any song and assign a video to it. When a song has an assigned video, a music video button will appear next to the song and let the user watch the video.

- Integrated Spotify login using 0auth with NextAuth allowing users to authenticate their Spotify account and access their user data in my app
- Implemented search feature using the Youtube api and storing song_id/video_id associations in a Mongo db database which are used to source an iframe allowing users to watch the video on my site
- Designed adaptive UI widgets that expand and collapse to make efficient use of screen real estate

Tech used: Javascript, HTML, SASS, React, Redux, Next, NextAuth, MongoDB, Mongoose, Spotify api, Youtube api

## Skills

Languages: Typescript, Javascript, Node, HTML, CSS, Rust, SQL, Python, Java \
Libraries and Frameworks: React, Redux, Next, Express, Warp, Mongoose, Diesel, socket.io, NextAuth, Chakra UI \
Tools: PostgreSQL, MongoDB, Linux, Postman, Docker
