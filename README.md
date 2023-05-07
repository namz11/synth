# Synth

_NOTE: This project is part of CS-554 coursework at Stevens for Spring 2023_

Synth is a web application that allows you to stream audio and find new tracks. Synth allows you to make playlists and look for songs, artists, albums, or playlists. You can also explore artist and album pages, as well as listen to top tracks by an artist. The music player allows you to manage core functions like play/pause, continue, and volume control, as well as view song information like artist, album, and song length. You can update your profile picture, login, and password as well as manage your profile details.

## Github Repo

[https://github.com/namz11/synth](https://github.com/namz11/synth)

## Set up

The root project contains the backend and frontend codebase for Synth. After cloning the main repo run the below command on the root of the project to clone the submodules.

```
git submodule update --init
```

### Backend

From the root of the project, navigate to /backend & run the below scripts -

1. Install the node_modules using npm

```
npm install
```

2. Run the server. This will run the server on [http://localhost:8888/](http://localhost:8888/)

```
npm start or npm run devStart
```

### Frontend

From the root of the project, navigate to /synth-frontend & run the below scripts -

1. Install the node_modules using npm

```
npm install
```

2. Run the client. This will run the client on [http://localhost:3000/](http://localhost:3000/)

```
npm run dev
```

## Production Builds

We have setup the following domains for our backend & frontend code using Vercel. They communicate with each other.

Main Website - [https://synth-music.vercel.app/](https://synth-music.vercel.app/)
Backend - [https://synth-backend.vercel.app/api/](https://synth-backend.vercel.app/api/)

## Staging Builds

We have setup the following staging environment for our backend & frontend code using Vercel to test our code.

Main Website - [https://synth-frontend-git-dev-namz11.vercel.app/](https://synth-frontend-git-dev-namz11.vercel.app/)
Backend - [https://synth-backend-git-dev-namz11.vercel.app/](https://synth-backend-git-dev-namz11.vercel.app/)

## Limitations

We are using the spotify api which limits the number of devices playing music simultaneously to only one. So irrespective of the user logged in at a time only one person can play music on one device.

## Contributors

We are the Bug Squashers.

<table>
  <tr>
    <td align="center"><a href="https://github.com/namz11"><img src="https://avatars.githubusercontent.com/u/14045632?v=4" width="100px;" alt="Narmit"/><br /><sub><b>Narmit Mashruwala</b></sub></a></td>
    <td align="center"><a href="https://github.com/iamvatsalpatel"><img src="https://avatars.githubusercontent.com/u/61371035?v=4" width="100px;" alt="Vatsal"/><br /><sub><b>Vatsal Patel</b></sub></a></td>
    <td align="center"><a href="https://github.com/amanP9"><img src="https://avatars.githubusercontent.com/u/83835770?v=4" width="100px;" alt="Aman"/><br /><sub><b>Aman Patel</b></sub></a></td>
    <td align="center"><a href="https://github.com/PaperPony"><img src="https://avatars.githubusercontent.com/u/46766544?v=4" width="100px;" alt="Dominick"/><br /><sub><b>Dominick Varano</b></sub></a></td>
  </tr>
</table>

## License

Synth is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
