# Project: Personal site [(access site here)](https://antoniosfiala.github.io/personal_site/)
Purpose of this project is to make a little website, a type of digital business card, that can connect people to various social networks where people can find more information or get in touch.

## Approach & purpose of the project
- Use open-source templates and resources
- Only amend what is required to make it 'my own'
- Generalise code to allow for easy extendability in the future
- Create detailed documentation here on GitHub
- Practice using GitHub
- More documentation [here](#Documentation)

## Mini architecture
The interaction of the various components and code-bases of the project. See [documentation](#Documentation) for changes in each component.

![alt text](https://github.com/antoniosfiala/personal_site/blob/new_code/Site_architecture.svg "Diagram")

## List of tools
- [The Noun Project](https://thenounproject.com) for icons used in the rectangles and the line dividers
- [Pixelmator Pro](https://www.pixelmator.com/pro/) availabe on [MacOS Appstore](https://apps.apple.com/us/app/pixelmator-pro/id1289583905?mt=12)
- [Atom.io](https://atom.io) text editor
  - [Chromo package](https://atom.io/packages/chromo-color-previews) to preview hex colours [GitHub here](https://github.com/Vertagon-Softworks/Chromo)
- [Google Chrome (MacOS)](https://www.google.com/intl/en_uk/chrome/) and Safari (Mac & iOS) for desktop and mobile testing
- Generate colour palette using [coolors.co](https://coolors.co/)
- GitHub markdown cheatsheet [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Favicon Generator](https://realfavicongenerator.net) used to create various sizes and code for site favicon 

---
**Colour-scheme**
- Dark orange: #E36414 ![alt text](https://github.com/antoniosfiala/personal_site/blob/new_code/assets/img/Colours/Dark_orange.png "Dark orange")
- Light Orange: #FB8B24 ![alt text](https://github.com/antoniosfiala/personal_site/blob/new_code/assets/img/Colours/Light_orange.png "Light orange")
- Light Green: #A8C256 ![alt text](https://github.com/antoniosfiala/personal_site/blob/new_code/assets/img/Colours/Green.png "Light green")
- Light Blue: #86BBD8 ![alt text](https://github.com/antoniosfiala/personal_site/blob/new_code/assets/img/Colours/Light_blue.png "Light blue")
- Pacific Blue: #004F62 ![alt text](https://github.com/antoniosfiala/personal_site/blob/new_code/assets/img/Colours/Pacific_blue.png "Pacific blue")

**References**
1. _'Freelance' bootstrap theme [GitHub repository](https://github.com/startbootstrap/startbootstrap-freelancer) under MIT licence_
2. _Base colour based on iPhone 12 Pro, 'Pacific Blue' hex codes found [here](https://colorswall.com/palette/27294/)_
3. _Social network icons using existing code and adding more using raw data at [fontawesome](https://fontawesome.com/icons?d=gallery)_
4. _Colours in GitHub markdown [stackoverflow](https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file)_
5. _Centering fixed position text in a div [stackoverflow](https://stackoverflow.com/questions/2861247/center-aligning-a-fixed-position-div)_
6. _Adding perspective to favicon logo [Pixelmator community](https://www.pixelmator.com/community/viewtopic.php?f=10&t=15154)_
---

## Documentation
**A. HTML**
  - Removed code from the template that was not required
  - Amended content (text, titles, images (found in 'D. Assets'))
  - Added different line break with icons
  - Amended hover over box behaviour
  - Added extra favicon lines of code

**B. JavaScript**
  - Removed references to unnecessary libraries for the contact form
  - Aside from that, code left as is

**C. CSS**
  - Spent majority of my time here
  - Generalised references with variables, particularly for colours
  - Added some new classes for custom text over the interest boxes

**D. Assets**
  - Created a profile picture
  - Downloaded and prepared assets (mainly in .svg) for line breaks
  - Downloaded and created icons for areas of interest using the defined colour pallet only
  - Colours to show in markdown documentation
  - Saved favicon elements here
  - Work_in_progress folder contains the Pixelmator files
