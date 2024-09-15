# Make Your Own Music Playlist App

## Desctiption
I want to make an app that lets users create their own music playlists. <br>
Users will be able to make multiples playlists with descriptions. <br>
Searching Youtube for tracks by artist names and track titles. That will be added to their playlists if it exists <br>
They will be able to add, delete, edit and reorder tracks and their arrangements. <br> 
They will be able to edit the names and descriptions of their playlists. <br> 


## Planning the routes
Let’s go ahead and establish the RESTful routing for app: <br>

- Action	Route	HTTP Verb 
- Index	‘/users/:userId/playlists'	GET
- New	‘/users/:userId/playlists/new’	GET
- Create	‘/users/:userId/playlists'	POST
- Show	‘/users/:userId/playlists/:playlistId'	GET
- Edit	‘/users/:userId/playlists/:playlistId/edit'	GET
- Update	‘/users/:userId/playlists/:playlistId'	PUT
- Delete	‘/users/:userId/playlists/:playlistId'	DELETE


















## Additional Ideas
- adding more ways to organize such as
    - Genres
    - BPM
    - Mood/Setting
    - Album
    - Length
- add a share feature?
- add Spotify search capabilities? 