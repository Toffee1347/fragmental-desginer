# Changelog

## [v2.1.0](https://github.com/danielhoward-me/chaos/tree/v2.1.0)

- Add presets, local and cloud saves through a backend and a login system

## [v2.0.1](https://github.com/danielhoward-me/chaos/tree/v2.0.1)

- Update links to reflect the new repository location

## [v2.0.0](https://github.com/danielhoward-me/chaos/tree/v2.0.0)

- Update all code to be written in TypeScript and compiled by webpack
- Change workflow to deploy tp vercel instead of github pages
- Add staging build option
- Change scroll bar + shape type styling

## [v1.3.0](https://github.com/danielhoward-me/chaos/tree/v1.3.0)

- Put missing line break in vertex rules help where one was missing
- Refactor vertex rules input system to find every permutation of characters which allows a word to be matched instead of single characters
- Add `∈` and `∉` characters to the vertex rules input and enforce the use of them when using sets
- Fix bug with generate points loading bar which wouldn't update until 100% was reached
- Fix bug where the cursour would always move to the end of the input when using special characters
- Fix bug where the indexes of the vertexes went anticlockwise instead of clockwise
- Fix annoyance when mobiles would auto capitalise in vertex rules
- Move vertex rules into a details drop down to make the UI feel cleaner
- Turn the project into a node project and create tools to generate help images automatically

## [v1.2.5](https://github.com/danielhoward-me/chaos/tree/v1.2.5)

- Add saving settings to help menu
- Add contents section to help menu to improve navigation
- Fix problem in help menu where it was spamming the history log with repeated entries

## [v1.2.4](https://github.com/danielhoward-me/chaos/tree/v1.2.4)

- Add functionality to download and upload saves

## [v1.2.3](https://github.com/danielhoward-me/chaos/tree/v1.2.3)

- Fix zooming issue on safari mobile
- Fix typo in help text

## [v1.2.2](https://github.com/danielhoward-me/chaos/tree/v1.2.2)
- Add keybings to allow pannels to be toggled easily
- Make close button sticky for more intuitive UI

## [v1.2.1](https://github.com/danielhoward-me/chaos/tree/v1.2.1)
- Update repositories [README.md](https://github.com/danielhoward-me/chaos/blob/v1.2.1/README.md)
- Update the help page to add much more detail

## [v1.2.0](https://github.com/danielhoward-me/chaos/tree/v1.2.0)
- Update the shape type selector to work by using a hidden select element
  - This is more inline with other behaviours of inputs being the values that will change the output of the program
- Begin to add basic saves functionality to be able to download and upload configurations
- Add option called `Vertex Rules` which outlines the rules used when picking a new vertex
  - This is implemented through a custom element called `tag-input`
- Rotate even sided polygons by half their internal angle to make them look more natural
- Improve canvas performance by rounding all coordinates to integers

## [v1.1.2](https://github.com/danielhoward-me/chaos/tree/v1.1.2)
- Change the line proportion option to be the distance from the point instead of the vertex since that is how it is done on other sites

## [v1.1.1](https://github.com/danielhoward-me/chaos/tree/v1.1.1)
- Update all references to the Sierpinski triangle to the chaos game with the new repository name

## [v1.1.0](https://github.com/danielhoward-me/chaos/tree/v1.1.0)
- Change the project from being focused on the Sierpinski triangle to being focused on the chaos game since it suits the project better
- Add a proportion option in shape settings which lets you decide how far along the line the point should be placed from the vertex

## [v1.0.2](https://github.com/danielhoward-me/chaos/tree/v1.0.2)
- Add [robots.txt](https://github.com/danielhoward-me/chaos/blob/v1.0.2/public/robots.txt) to make it easier for search engines to index the site

## [v1.0.1](https://github.com/danielhoward-me/chaos/tree/v1.0.1)
- Add text at the bottom of the settings section which displays the app version
- Create this file to keep track of changes
- Add a link to this file next to the app version
