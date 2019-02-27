# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="http://g.recordit.co/fbMFaPmdSB.gif" width=250><br>
Clicking on a movie will display its details in another view

<img src="http://g.recordit.co/yWXdQQETIp.gif" width=250><br>
Tab bar navigation with the option to view superhero-related movies in a grid view (collection view layout)

---

## Flix Part 1

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF
<img src="http://g.recordit.co/cvEixKlqKy.gif" width=250><br>

### Notes
While building the app, I ran into a problem in which I could not get my stimulator to display what was on my main storyboard. 
This was because I did not refer tableView.dataSource and tableView.delegate to self and tableView.rowHeight to the row height 
value of my cell. 
