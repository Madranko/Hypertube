# Hypertube
A web application that allows the user to research and watch videos.
### Code
1. Front-end: ReactJS<br/>
2. Back-end: PHP/Laravel<br/>
3. Video streaming: NodeJS<br/>
### Realization<br/>
#### User part<br/>
   • The app is allow a user to register asking at least an email address, a username,
     a last name, a first name and a password.<br/>
   • The user is able to register and connect via Omniauth(Google+, 42 School). <br/>
   • The user is able to connect with his/her username and password. He/She
     able to receive an email allowing him/her to re-initialize his/her password.<br/>
   • The user must be able to select a preferred language that will be English by default.<br/>
   • Modify the email address, profile picture and information.<br/>
####  Library part<br/>
   This part can only be accessible to connected users.<br/>
   This part has:<br/>
    • A research field.<br/>
    • A thumbnails list.<br/>
#### Research<br/>
   The search engine interrogate external sources, and return the ensemble of results in thumbnails forms.<br/>
   The list is automatically charged asynchronically.<br/>
   The page is sortable and filterable according to criteria such as name, genre, the
   IMDb grade, the gap of production year etc...<br/>
#### Video Part<br/>
   To launch the video on the server - if the file wasn’t downloaded prior –
   launch the download from the associated torrent on the server, and stream the video
   from that one as soon as enough data has been downloaded to ensure a seamless watching
   of the video.<br/>
   Once the movie is entirely downloaded, it saved on the server, so that we
   don’t need to re-download the movie again. If a movie is unwatched for a month, it will
   be erased.<br/>
   If subtitles are available for this video, they will be downloaded and
   available for the video player.<br/>
   
# Language management example
![language](http://g.recordit.co/ISeWi5xEqZ.gif)
# Authorization via Google+
![google](http://g.recordit.co/KVtmWZqOvq.gif)
# Simple film search
![search](http://g.recordit.co/27X32cVNQN.gif)
# Film page example
![film-page](/readme/screen.png)
# Video streaming
![stream](/readme/movie.gif)
