TO-DO List
=======

This document lists all the things I should look more carefully in the future.

- [ ] fix the footer. it uses z-index and overlaps with the content.
- [ ] some links (report, map and heat) need to be there even when the nav bar is small.
- [ ] the popup needs graphical improvements.
- [ ] add Tim to the list of authors in this repo.
- [ ] add elastic search client-side for the maps (load from the DB just the points on the visualised area of the map).
- [ ] improve the statistics page (it's not graphically coherent with the rest of the best site, it also doesn't contain explanation).
- [ ] "remove this problem" link and form (first attempt to collect feedback to delete points).
- [ ] insert presentation text on the index page.
- [ ] user registration using social log in.
- [ ] store the categories in the DB (pollution, pavement, graffiti, tree, flyposting, litter, light, name sign, syringes, abandoned building, pothole, street furniture) [sources: [Manchester City Council](), [London City Council](https://www.gov.uk/browse/housing-local-services/recycling-rubbish)].

Things done:

- [x] add zoom buttons on the heat map (+ and - like in /map).
- [x] the upload module should store just one resized picture (500px).
- [x] Android and iOS link to icon added (it works when you save the webpage in the home)
- [x] use Jinja2 templates ihneritance to avoid redundand code.
- [x] automatic centering of the maps according to the current coordinates.