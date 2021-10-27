# Halo History

My Website is designed to Introduce and Reinform possible customers of the Halo Franchise. The Site will work as a historical look over the franchises 20 years and encourage more people to get interested and involved in the series. I will use different forms of media such as Images and Video to sumarise more information in an entertaining format for each game in the series. I will also offer a newsletter sign up form, anyone who signs up will recieve weekly updates regarding the newest game yet to be released. It will also provide different story related facts and value beyond just news.

## UX

As stated by the introduction, the site will aim to draw in people to gain interest in the Halo franchise. To do this, the site will use a simple homepage to encourage new users to find out more. At the same time it will be easy for pre-existing users to find the content that they may be interested in. The Games page will make it easy to digest simple information about each game. Using YouTube embeded trailers I will also allow users to watch a sumarised version of each game to provide further content.

The colour scheme is based on a simple white and deep blue to contrast the text for ease of reading. The Header will use this variation of white as the primary colour and all the text contained within it shall be blue. This will keep the heading at the central focus point and allow easy navigation. The rest of the sites content will rely on the deep blue in the background and allow bright text to be easily noitced and read. I used the Wave Evaluation tool to ensure the tones of each colour worked appropriatly for all users.

![Screenshot showing website contract score](screenshots/contrast-screenshot.PNG "Screenshot of Wave Elvaluation Tool")

I have included wireframes and my sites main pages bellow to detail the proposed structure.

![Initial sketch of the landing/home page](screenshots/home-page-sketch.PNG "Home Page Sketch")
![Initial sketch of the games page](screenshots/games-sketch.PNG "Games Page Sketch")
![Initial sketch of the Newsletter page](screenshots/newsletter-sketch.PNG "Newsletter Page Sketch")

After the creation of my site I kept as close to my wireframes as possible. However when making the games page I ran into a lot of formatting issues. This made it very difficult to display a trailer, images and all the game descriptions in a mobile responsive way. To get around this I turned the entire section into solid content blocks which would allow an easy flow of Title->Description->Trailer. I also opted to include a description of the newsletter, making the content more clear to new users.

User Stories as followed:

### New Users

* I am wanting to learn what Halo is.
* I am interested in the history and timeline of the games.
* I am wanting to see what each game looks like and the story it presents.

### Returning User

* I am checking back for any updates regarding the newest game
* I am wanting to sign up for the newsletter to get further information

## Features

## Existing Features

### Index/Home Page

#### Nav Bar

My Navigation bar consists of an unorderd list that has been aligned to the correct space on the screen using flexbox.

The Nav bar will allow easy navigation across all pages of the site. It uses a simple active class to always inform the user what page they are on. It uses a similar class to also show an underline when a new page is hovered over. It exists on every page of the site, negating the need to use the back button at all.

![Screenshot showing the Navigation bar on desktop](screenshots/nav-bar.PNG "Nav Bar from Site")

#### Hero Image

When users load into the main page for the first time they will be greeted by a welcome message. It is highlighted by using a hero image that has been blurred. By being blurred it will make the text stand out. It features a button that will directly link a user to the main content of the website. By doing this I'm allowing returning users to quickly find what they are looking for.

![Screenshot showing the hero image on desktop](screenshots/hero-image-screenshot.PNG "Hero Image welcome message")

#### Site Explination

#### Game Explination

#### Footer

## Future Plans

## Testing

## Technologies used

HTML

CSS

Google Fonts

Gitpod

Wave Evaluation Tool

Github

## Bugs

During early development I had incorrectly assigned the list-style for my navigation in the wrong area. It was only when resizing to test responsiveness I realised it was there but hidden as it was the same colour as thhe background. I was able to fix this by moving the list style rule from the #controls ul to #controls li.

For some duration my footer text was not on one line. I was unable to find out why, I then discovered that the divs representing the content blocks on the main page were not the same height as the entire section was set to be. By Setting them down from 400px to 300px the same as the #about section. The content did not change, however the footer text rearanged itself to fit on one line.

While coding, encountered a Blue Screen of Death Error which erased some work half way through some code. Had to wipe clean to be able to structure the timeline properly again.

For a majority of development I had used floats to space and align content. However when attempting to make the site mobile responsive it would create many issues. To fix this I learnt about flex and converted most of my content blocks and the navigation bar to use this method. This would allow all the site content to correctly show up on mobile/tablet devices.

## Credits

### Site Content

My background image was taken from:

https://free4kwallpapers.com/halo-wallpapers

All game descriptions are taken from:

https://www.halowaypoint.com/en-gb

Halo Infinite image/wallpaper taken from:

https://www.halowaypoint.com/en-us/forums/29568daf8cd14083bd1b70a810bf3581/topics/halo-infinite-xgs-press-kit-2020/be564010-250c-47c9-af39-ebb9c7f27f18/posts

Halo: Combat Evolved Trailer from:

https://www.youtube.com/watch?v=v0kHiEME0Vk

Halo 2 Trailer from:

https://www.youtube.com/watch?v=ATUSC9ohowk

Halo 3 Trailer from:

https://www.youtube.com/watch?v=yMwXD_zQfRw&feature=emb_title

Halo 4 Trailer from: 

https://www.youtube.com/watch?v=DIspQ1NmGf4

Halo 5 Trailer from:

https://www.youtube.com/watch?v=Rh_NXwqFvHc
## Acknowledgements

Initial planning and methods were inspired by the Love Running Walkthrough

Code to add aria-label to my background image was found on Stackoverflow at:

https://stackoverflow.com/questions/40555111/what-is-the-best-way-to-use-a-background-image-on-a-div-yet-remain-accessible/40562191

Flex box code and tutorial to make content responsive was found here:

https://www.w3schools.com/css/css3_flexbox_responsive.asp

https://flexboxfroggy.com

Code to add images to readme:

https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github

**This project is for educational purposes only**