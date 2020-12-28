# Project: Personal site [(link)](https://antoniosfiala.github.io/personal_site/)
Making a little website, a digital business card, that can connect people to various social networks where people can find more information or get in touch.

## Approach & purpose of project
- Use open-source templates and resources
- Amend only what is required to make it 'my own'
- Generalise code to allow for easy extendability in the future
- Create detailed documentation here on GitHub
- Practice using GitHub
- More documentation [here](#Documentation)

## Mini architecture
The interaction of the various components and code-bases of the project.
[Image link](https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&title=Site_architecture.drawio#R7ZjJbtswEIafxscG2qMcHdmJUSRtURVoemSksUSUFgWK3vL0HVrU7jgL0jhFbR%2FM%2BTlcxO8nRXhkB4vNtSB5estjYCPLiDcjezKyLNM0PPxRyrZULi7OSyERNNZJjRDSB9CiodUljaHoJErOmaR5V4x4lkEkOxoRgq%2B7aXPOuqPmJIGBEEaEDdWfNJZpqfrWeaPPgCapHtk19LwXpMrVQpGSmK9bkj0d2YHgXJalxSYAptauWpay3dUjtfW8BGTyOQ224cOXr1Nq%2BUUxnbrB9ys5WX%2Fyy15WhC31844sj2F%2Fl%2FdYSFThmsrZEiMj5YWkWVIl4Eh1jn5Cua1WTfBlFoMa2cTqdUolhDmJVO0afYJaKhdMV895JjV401ExZSzgjItdX%2FbcVV%2FUCyn4b2jVeLuP7qGllx%2FUCaNJhlqEawRYebkCISnCHesKyfN6%2BqoONo%2BurlkzQ68DX4AUW0zRDSzbKZtom%2Fua%2BrrxjO1pLW35xa58TrRPk7rrhiUWNM4XoDUHaMdnGM9%2B3N68MS4V677MIb7YBT929uHzrXt7h6%2FCxGCu3FTg0Gi0m100wQV6G0Jul1B9wrQQmdYeRN7fImQNCAWKUBCG%2FyUg58MBsgeALhWgz2RFwkjQXL4vJwL%2BPNp7DkY%2B3M%2BPxck8OidnwGmiOI2LAmRx2kvt18zRGLl7bho9MJDFY3VjUy9sRoqCRl0WsKHyDsuGLv9S5TNXR5NNq2qyrYIMJ39XdaCCVisVNs12UdXuMPfdzCEe3Bx7ePDp%2BFJE8LR1JREJyKfe5kPcLZzuHpqVJoARSVfd6e5DrEf4xik%2BSOMmo%2Bsmp%2B%2BS8jF1q%2FYdtN9Rz5ZO%2F%2FZTrsOgI7QF2bbScpVQHJiw2bO%2FYxyeVy%2Ff6uZjoZxBY%2F%2Bawet3hHfaEQduRR98R3g9g7mv3BG233Nev6MX74jOKf0GNj0%2F2fTA3fDfsunAXcez6fMOYvN9D24Mmz9kyvTmXy17%2Bgc%3D)
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAXMAAAFBCAYAAACFCE80AAAF/3RFWHRteGZpbGUAJTNDbXhmaWxlJTIwaG9zdCUzRCUyMkVsZWN0cm9uJTIyJTIwbW9kaWZpZWQlM0QlMjIyMDIwLTEyLTI4VDIxJTNBMDAlM0E0Ny4yMzhaJTIyJTIwYWdlbnQlM0QlMjI1LjAlMjAoTWFjaW50b3NoJTNCJTIwSW50ZWwlMjBNYWMlMjBPUyUyMFglMjAxMF8xNl8wKSUyMEFwcGxlV2ViS2l0JTJGNTM3LjM2JTIwKEtIVE1MJTJDJTIwbGlrZSUyMEdlY2tvKSUyMGRyYXcuaW8lMkYxMy45LjklMjBDaHJvbWUlMkY4NS4wLjQxODMuMTIxJTIwRWxlY3Ryb24lMkYxMC4xLjUlMjBTYWZhcmklMkY1MzcuMzYlMjIlMjBldGFnJTNEJTIya1NpdTRpb2o4eTZuaWVfVjlnZEklMjIlMjB2ZXJzaW9uJTNEJTIyMTMuOS45JTIyJTIwdHlwZSUzRCUyMmRldmljZSUyMiUzRSUzQ2RpYWdyYW0lMjBpZCUzRCUyMkdvWTFCRS1aVFQyYkFvaWJrRTdRJTIyJTIwbmFtZSUzRCUyMlBhZ2UtMSUyMiUzRTdaakpidHN3RUlhZnhzY0cycU1jSGRtSlVTUnRVUlZvZW1Ta3NVU1VGZ1dLM3ZMMEhWclU3amdMMGpoRmJSJTJGTSUyQlRsY3hPOG5SWGhrQjR2TnRTQjVlc3RqWUNQTGlEY2plekt5TE5NMFBQeFJ5clpVTGk3T1N5RVJOTlpKalJEU0I5Q2lvZFVsamFIb0pFck9tYVI1VjR4NGxrRWtPeG9SZ3ElMkI3YVhQT3VxUG1KSUdCRUVhRURkV2ZOSlpwcWZyV2VhUFBnQ2FwSHRrMTlMd1hwTXJWUXBHU21LOWJrajBkMllIZ1hKYWx4U1lBcHRhdVdwYXkzZFVqdGZXOEJHVHlPUTIyNGNPWHIxTnElMkJVVXhuYnJCOXlzNVdYJTJGeXkxNVdoQzMxODQ0c2oyRiUyRmwlMkZkWVNGVGhtc3JaRWlNajVZV2tXVklsNEVoMWpuNUN1YTFXVGZCbEZvTWEyY1RxZFVvbGhEbUpWTzBhZllKYUtoZE1WODk1SmpWNDAxRXhaU3pnakl0ZFglMkZiY1ZWJTJGVUN5bjRiMmpWZUx1UDdxR2xseCUyRlVDYU5KaGxxRWF3UlllYmtDSVNuQ0hlc0t5Zk42JTJCcW9PTm8lMkJ1cmxrelE2OERYNEFVVzB6UkRTemJLWnRvbSUyRnVhJTJCcnJ4ak8xcExXMzV4YTU4VHJSUGs3cnJoaVVXTk00WG9EVUhhTWRuR005JTJCM042OE1TNFY2NzdNSWI3WUJUOTI5dUh6clh0N2g2JTJGQ3hHQ3UzRlRnMEdpMG0xMDB3UVY2RzBKdWwxQjl3clFRbWRZZVJON2ZJbVFOQ0FXS1VCQ0clMkZ5VWc1OE1Cc2dlQUxoV2d6MlJGd2tqUVhMNHZKd0wlMkJQTnA3RGtZJTJCM00lMkJQeGNrOE9pZG53R21pT0kyTEFtUngya3Z0MTh6UkdMbDdiaG85TUpERlkzVmpVeTlzUm9xQ1JsMFdzS0h5RHN1R0x2OVM1VE5YUjVOTnEycXlyWUlNSjM5WGRhQ0NWaXNWTnMxMlVkWHVNUGZkekNFZTNCeDdlUERwJTJCRkpFOExSMUpSRUp5S2ZlNWtQY0xaenVIcHFWSm9BUlNWZmQ2ZTVEckVmNHhpayUyQlNPTW1vJTJCc21wJTJCJTJCUzhqRjFxJTJGWWR0TjlSejVaTyUyRiUyRlpUcnNPZ0k3UUYyYmJTY3BWUUhKaXcyYk8lMkZZeHllVnklMkZmNnVaam9aeEJZJTJGJTJCYXdldDNoSGZhRVFkdVJSOThSM2c5ZzdtdjNCRzIzM05ldjZNWDc0ak9LZjBHTmowJTJGMmZUQTNmRGZzdW5BWGNlejZmTU9Zdk45RDI0TW16OWt5dlRtWHkxNyUyQmdjJTNEJTNDJTJGZGlhZ3JhbSUzRSUzQyUyRm14ZmlsZSUzRZRqilwAACAASURBVHhe7Z0JXFXFF8cPgqKsouSuoSUpYi6IVi7kjqml5FrmLphKCuaSpob+NZcEDTPB3WxztzQxS8NcUsQld1wT951VEZH/54w9QmS57zHvvfve+83n0yeEuWfOfM/M7807M/deK0IBARAAARAweQJWJt8DdAAEQAAEQIAg5hgEIAACIGAGBCDmZhBEdAEEQAAEIOYYAyAAAiBgBgRMRsz9/f3tMjIy6llbW9cqWrRorWLFinkQUaXHjx+XzsjIsM/IyLDNzMy0NoOYoAsgAAIGImBlZZVh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" style="cursor:pointer;max-width:100%;" onclick="(function(img){if(img.wnd!=null&&!img.wnd.closed){img.wnd.focus();}else{var r=function(evt){if(evt.data=='ready'&&evt.source==img.wnd){img.wnd.postMessage(decodeURIComponent(img.getAttribute('src')),'*');window.removeEventListener('message',r);}};window.addEventListener('message',r);img.wnd=window.open('https://viewer.diagrams.net/?client=1&page=0&edit=_blank');}})(this);"/>


## List of tools
- [The Noun Project](https://thenounproject.com) for icons used in the rectangles and the line dividers
- [Pixelmator Pro](https://www.pixelmator.com/pro/) availabe on [MacOS Appstore](https://apps.apple.com/us/app/pixelmator-pro/id1289583905?mt=12)
- [Atom.io](https://atom.io) text editor
  - [Chromo package](https://atom.io/packages/chromo-color-previews) to preview hex colours [GitHub here](https://github.com/Vertagon-Softworks/Chromo)
- [Google Chrome (MacOS)](https://www.google.com/intl/en_uk/chrome/) and Safari (Mac & iOS) for desktop and mobile testing
- Generate colour palette using [coolors.co](https://coolors.co/)
- GitHub markdown cheatsheet [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

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
---

## Documentation
**A. HTML**
  - Removed code from template that was not required
  - Amended content (text, titles, images (found in 'D. Assets'))
  - Added different line break with icons
  - Amended hover over box behaviour
  - Added extra favicon lines of code

**B. JavaScript**
  - Removed references to unnecessary libraries for contact form
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
