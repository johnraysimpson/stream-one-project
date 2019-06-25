# Stream One Project - Creat a Website for a Band

In this project I was briefed to create a static website for the band 'The Monkees'. Although this is not a fictional band, it is assumed they are still performing to this day and are available for booking for events. The assets given were used as much as possible to ensure fans of the band can listen and watch The Monkees content, book them for any occasion and find further imformation about them with external links.

## UX

This website is for fans of the Monkees to access content with ease and potentially book them. With links continuously in the footer to book and visit social media platforms, these are also icluded in appropriate pages (e.g. a Spotify link on the listen page, a YouTube link on the videos page).

The colour scheme is reminiscent of the 1960s and remains consistent in each page, I felt this may get confusing for users as they may not know which page they are on, so I felt it would be useful to add imagery to ensure they are more aware of this.

Many of the links will open a new tab, allowing the user to return to the original website easily.

I used Font Awesome icons to make it obvious where the user would be going.

## Features

All features are either from the Bootstrap library or written by myself.

### Existing Features

A vertical navbar for large screen sizes was created using CSS transitions, it allows users to gain more information by hovering over icon links.

Hovering other links will fade to different colours, allows users to be aware that it is clickable.

Form filling conditions allow the user to ensure they are filling in the form correctly.

Songs in the Listen page are in a table, this allows users to have access to more information about those songs.

### Features left to implement

In the future, it would be good to have a message appear letting the user know that their booking request was successful after clicking the submit button.

I have noticed that on the listen page, you canhave multiple songs playing at once. It would be nice to have a feature that a song playing is stopped when another is played.

The "type of event" part of the form on the booking page doesn't need to be selected for the form to go through, some functionality in which a user has to choose one would be ideal.

## Technologies used

* HTML
* CSS
* Bootstrap (3.3.7)
* Font Awesome (4.7.0) (provided by Bootstrap)

## Testing

* The vertical navbar was a personal challenge to see if I could make it work, it took some trial and improvement with z-indexes, positions etc. and I eventually got there.
* The form has certain required fields in order to submit, I have tested these but inputting nothing and seeing what happens. Although the phone number isn't required but if you do send one it as to be 11 characters long (as with UK phone numbers). However, the required attribute for the "type of event" dropdown box does not seem to work.
* I have tested each page on multiple screen sizes, including desktops, tablets and various mobile phones (I asked other people to test this as well). I made the decision that hover transitions are wasted on smaller devices so opted for a more conventional navbar for screen sizes that are smaller than desktop.
* I tested any media assets such as songs or videos to ensure they were working properly, I also tried these on other browsers.
* Links to social media for the Monkees will take you to the actual corresponding social media in a new tab.

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/johnraysimpson/stream-one-project.git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits

### Content

* The information on the About pagewas lifted from the Wikipedia pages of the band and the members.

### Media

* Most of the assets were provided by Code Institute, any other imagery were from free image websites.

### Acknowledgements

* Thanks to many people I worked with who were around for The Monkees, they gave me many ideas to make this site look the best it could.