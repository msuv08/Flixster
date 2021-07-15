# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF
`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)

<img src="YOUR_GIF_URL_HERE" width=250><br>

### Notes
Describe any challenges encountered while building the app.

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

For this project, pods were also a necessity to grab the images of movie posters from [The Movie Database API](http://docs.themoviedb.apiary.io/#). AlamofireImage had to be installed as a dependency, and a workspace had to be created through terminal. Understanding how to do so was rudimentary, but the bigger concept was understanding how to extend this knowledge outside the scope of Flixy.
