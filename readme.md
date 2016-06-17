## Surf and Paddle Website Layout Assignment

### Task

- The point of this assignment is to exactly recreate a functional front website page from an image using Pixel Perfect
- Good for practicing as a potential job task later, as a design team often give an image and will care exactly where each and every pixel is placed
- Because I'm making the website responsive, I'm shooting for basically pixel perfect when the browser window is approx 1250px wide
-

A-Ha Moments:
  - Several times the first day I would get a small detail perfect but then fixing something else would mess up the spacing of that small detail, and with all the back and forth I got a lot less done that day than I would have if I had (drum roll for the big takeaway) **focused on the big issues first and then trickled down to the detail work.** Think of it like the old object lesson of filling up a jar: big rocks first, then small rocks, then sand, and that way everything fits nice. If you fill it with sand and little rocks first, you won't have room for all the big rocks. To this end, on day 2 I did the entire html framework before starting to fiddle with the CSS. HTML tweaks can be done as necessary, but having the whole frame in place makes it much easier to know the side effects CSS changes might have on later elements. (this thought expanded in week 1 blog post: https://medium.com/@christian.straubhaar/week-1-reflections-a-nice-a-ha-moment-738db3596108#.oxi8hv3sc)

#### Assets
-  "Comments", "Read Later", and "Share This" asset hints from http://fontawesome.io/cheatsheet/:
  1. comment signal: fa-comment-o [&#xf0e5;]
  2. share sign: fa-share-square-o [&#xf045;]
  3. read later: fa-cloud-upload [&#xf0ee;]
  4. search magnifying glass: fa-search [&#xf002;], rotated so used fa fa-search fa-rotate-90

Minor Issues, etc.:
  - Had issues with line height, had to make sure it was all set to the same height as the text, which seems like an odd issue to have pop up
  -

Nifty things:
  - I was trying to figure out how to make the search bar appear next to the icon and Jess showed me a cool way to make it appear to the side using hover pseudo-selector and the transition attribute
  <!-- input{
    width: 0;
    margin: 0;
    padding: 0;
    border: none;
  }
  .search i:hover + input{
    width: 3rem;
    transition: 1s;
  } -->
