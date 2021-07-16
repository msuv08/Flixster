# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [X] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://user-images.githubusercontent.com/49384703/125909354-00450d59-4fba-477a-9b78-4004f66338f1.gif" width=250><br>

### Notes
For Part 2, Flix had to incorporate a second tab, as well as a detailed view of movies after a poster is clicked on. To accomplish this, cells were used, and segues passed data on to a new view controller, which appears modally with full details on the movie.

Another component was the new tabbar navigation system; a `Superhero` tab was added on the right, with the `Now Playing` movies tab on the left. The superhero tab includes the UIGridViewCollection, with a list of movies similar to `Black Widow`. To achieve this similar movie request, the [Get Similar](https://developers.themoviedb.org/3/movies/get-similar-movies) endpoint was used from [The Movie Database API](http://docs.themoviedb.apiary.io/#).

All credit attributed to [<img src="https://user-images.githubusercontent.com/49384703/125910420-674ff360-46ca-4dd9-b7ab-8fe195d92b7e.png" height=15>](https://developers.themoviedb.org/3/getting-started/introduction).

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://user-images.githubusercontent.com/49384703/125144291-fefa9d80-e0e2-11eb-8e31-2a85145d4475.gif" width=250><br>

### Notes
Table views were also required to properly display the cells of movie titles in Flixy, and figuring out how to use them was the main purpose of this app. Tables are common in many apps, and are used for various purposes, especially in popular social media apps (stories in Facebook, Twitter threads, etc.). Understanding how to recycle used cells was an interesting topic, and saved a lot of memory in Flixy's runtime.

For this project, pods were also a necessity to grab the images of movie posters from [The Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction). AlamofireImage had to be installed as a dependency, and a workspace had to be created through terminal. Understanding how to do so was rudimentary, but the bigger concept was understanding how to extend this knowledge outside the scope of Flixy.
