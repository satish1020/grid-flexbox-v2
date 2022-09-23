<p align="center">
  <a href="https://frontendmasters.com/courses/css-grid-flexbox-v2/">Frontend Masters: CSS Grids and Flexbox in Responsive Web Design v2</a>
</p>

[![Frontend Masters](https://static.frontendmasters.com/assets/brand/logos/full.png)][fem]

[Please click here][course] to head to the course website.

# Issues and Pull Requests

Please file issues and open pull requests here! Thank you! For issues with project files, either file issues on _this_ repo _or_ open a pull request on the projects repos. This repo itself is the course website.

# License

The content of this workshop is licensed under CC-BY-NC-4.0. Feel free to share freely but do not resell my content.

The code, including the code of the site itself and the code in the exercises, are licensed under Apache 2.0.

# Attributions

Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>

[fem]: https://frontendmasters.com/
[course]: https://frontendmasters.github.io/grid-flexbox-v2


# Video Notes:
flex-basis will spread the block to the percentage of the screen, it is kind of like width.  if there are 4 boxes, we gave the flex-basis as 22%

flex-wrap has default as row and no wrap.

we can specify flex-wrap: row- wrap or flex-wrap: column- wrap etc..

we can also rearrange the columns using order. So that the important content can be displayed first for search engine optimization.

we might need to play around with object-fit or object-position to make sure that images look as needed in different mobile or desktop or tablet.
Media Queries:

Tablets  are around  usually its 800 px width and mobile are 550px width plus

Generally when designing a responsive app. Its good practice to write mobile first and later tablet and desktop versions.

So when writing mobile styles first give min-width at the top so that this sets a minimum width standard, but later this can be overridden in the media queries of tablet as well as Desktop versions.

Where as some web apps are not responsive where in you modify the existing code, or if desktop version is more important when compare to mobile or if desktop is more complicated

In those scenarios, give the max width first and then override these with media queries of mobile and tablet.

gap is. a new thing in flex

flex-basis can be set for different desktop, mobile and tablet


rem is the spacing relative to the html, where as em is relative to the text. gap: 1.2 em, it will scale with respect to text.

1em in an h1 is much larger than 1em in a paragraph. so em will change based on which html element you are applying to. Where as 1 rem is standard which is arround 16px.

we give flex-basis: auto in cases where we want the width of the html element to be as wide as possible.

the trick is having even number of nav items arround the logo.

if the number of items on one side of nav is 3 and the other side is 2. Then by using margin: auto this will be mitigated to a certain extent. 