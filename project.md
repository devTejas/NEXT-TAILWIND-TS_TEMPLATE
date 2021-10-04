# Functionality

- For animations - [react.useAnimations](https://react.useanimations.com/)

## /sheets

- shows various sheets on /sheets page
  - every item in /sheets page is a list item using [react-flip-move](https://www.npmjs.com/package/react-flip-move)
  - the item shows clicks, users can like it, give comments

## /sheets/sde-sheet - use gdocs/gsheets api

- if clicked on any sheet - open the sheet in a new tab in a table format using [react-table](https://www.npmjs.com/package/react-table)
  - Table can be changed as well - based on category, shuffle, ascending, descending
  - Every problem is a row/list_item by react-flip-move
  - Columns - SL.NO, CheckBox(for checking if problem solved), problem(link/text), solution(link/text), hint(are hidden)
  - if user logins then he can save his progress as well

## /author

- shows author profile - pic, name, email, social accounts, work
- Author posts(anything) -
- try to have a follow button that sends updates & activites of the author
- try to get updates of the author from various platforms like youtube/
- fetch the author's latest activity from various platforms like youtube/twitter/ (limit the no of items to 10)

## /videos

- show youtube videos(in sort), playlists
- here it will be react-flip-move as a list or grid
- allow the users to fetch from a particular channel by selecting a channel or by searching the name of the channel
- if user plays a video then show him turnOffTheLighs button with a click sound

## /editor

- an inbuilt code editor that opens when a problem link is clicked

## /striverFan

- a small intro about the creator of the website & it's contributors (also show about the help needed)
-
