# Netflix Clone / Fullstack

![Netflix](/public/static/netflix-clone.png)

## This project Was made using Next.Js, JavaScript and CSS (and Framer-Motion) for the Frontend.

### As for the Backend, I used Hasura GraphQl and Magic Link for the authemtification.

Hasura and GraphQl are two great tools to use for the backend. But as for authentification,
I prefered to use Magic Link, which doesn't ask the user to enter any password that he/she
will forget sometimes in the future. That's why I prefered that service, where you only have
to enter your email address to register. It's also very secure!

Hasura stores the user's _email address_ (not password) and stores the user's choices
(if you like a video, that specific video should be found in **My List**, if you dislike the video, that video
will be retrieved from your **list**).
