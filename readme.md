<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216824024-d405b765-adaa-4f15-83ef-47b83fc923eb.png"></p>

## This project  allows users to create a music room and invite listeners to join in and listen to music together.
It was made together with the help of [ReactJS](https://reactjs.org/) and [Django](https://docs.djangoproject.com/en/4.1/) using [Material UI](https://mui.com/material-ui/getting-started/overview/) templates.
Host has the power to select *which song to play, how many members* to allow inside a room and will need to authenticate their Spotify account with the application to continue.
Listeners will have the liberty to *join a room* through a given valid room code and can together *vote\not vote to skip, play/pause* the particular playing song.

Screenshots:

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216823370-3b15b98e-7729-47b6-bac2-f8d4478def5b.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216823440-925e8cc9-2edf-4a4f-9818-a671bd74ca69.png"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216823472-aa56a12c-0a20-44ce-a058-f1c20cbc3da7.png"></p>

We can also see the *progress bar* of the currently playing song. The host will have the pause to independently control the play/pause and skipping of songs **(The user needs to have a Spotify Premium account to perform these functions)**:

<p align="center"><img src="https://user-images.githubusercontent.com/84025779/216823611-0a071837-f35d-42f5-b6be-7ec3af7c539c.png"></p>

## Available Scripts

In this project directory, head inside the music_controller directory:

`cd music_controller`

and run:

`python .\manage.py runserver`

This starts our web server
Open http://localhost:8000 to view it in the browser.

In order to view the server in development mode, open a new terminal and move into the frontend directory and run:

```
cd music_controller
cd frontent
npm run dev
```

You will also see lint errors (if any) inside the console of the browser.

## Learn More

You can learn more about how to develop your own server using similar tools by following [Django](https://docs.djangoproject.com/en/4.1/), [ReactJS](https://reactjs.org/docs/getting-started.html) and [Material UI](https://mui.com/material-ui/getting-started/overview/) documentation.

