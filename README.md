# Daniel Hogan

danielxhogan@gmail.com | linkedin.com/in/danielxhogan | github.com/danielxhogan | danielhoganofficial.com \
541-761-3824 | Central Point, OR 97502 | US Citizen

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

- Dockerized the entire app so the website can be deployed with one command
- Built an authentication system that generates auth tokens on login, checks authentication at every level (UI rendering, event handlers, api endpoints), and prevents unauthorized behavior
- Developed an interactive UI using React that conditionally renders based on users login status, updates when a user creates or deletes new posts, and is fully responsive
- Established websocket connections between the server and clients for real time communication in the review and comment sections
- Engineered an LRU (Least Recently Used) caching layer for the api using Redis

Tech used: Typescript, Node, React, HTML, CSS, Redux toolkit, Next, PostgreSQL, Redis, Docker, ChakraUI, Rust, Warp, Diesel, JWT, Bcrypt, TMDB api, DigitalOcean

### MVPlaylist

_Turn your Spotify playlist into a Youtube music video playlist_

website - mvplaylist.vercel.app \
Github: github.com/danielxhogan/mvplaylist \
Demo: youtube.com/watch?v=70tjwO3O_Q4

<ins>Overview</ins> \
MVPlaylist is a website that allows users to log in to their existing Spotify account. It lets them view their playlists and play songs in the browser. They can also search Youtube for videos related to any song and assign a video to it. When a song has an assigned video, a music video button will appear next to the song and let the user watch the video.

- Integrated Oauth Spotify login using NextAuth allowing users to authenticate their Spotify account and access their user data in my app
- Implemented search feature using the Youtube api and storing song_id/video_id associations in a Mongo db database which are used to source an iframe allowing users to watch the video on my site
- Designed adaptive UI widgets that expand and collapse to make efficient use of screen real estate

Tech used: Javascript, Node, React, HTML, SASS, Redux, Next, MongoDB, Mongoose, NextAuth, Spotify api, Youtube api

## Skills

Languages: Typescript, Javascript, Node, HTML, CSS, SQL, JSON, Rust, Python, Java \
Libraries and Frameworks: React, Redux, Next, Express, Jest, socket.io, Mongoose, NextAuth, Warp, Diesel \
Tools: PostgreSQL, MongoDB, Redis, Linux, Git, Docker, Postman
