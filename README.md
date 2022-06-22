# Advanced CSS
From [Udemy - Advanced CSS and Sass Flexbox, Grid, Animations and More!](https://www.udemy.com/course/advanced-css-and-sass/)

## Natours project
[Natours - WIP](https://nathalie-anneessens.github.io/advanced-CSS/Natours)

### Passe 1 - CSS
- [x] Header
### Passe 2 - HTML & SASS
- [ ] Intro Section
- [ ] About Section
- [ ] Features Section
- [ ] Tours Section
- [ ] Stories Section
- [ ] Booking Section
- [ ] Footer
- [ ] Navigation
### Passe 3 - Responsive
- [ ] Responsive


## Trillo Project (Flexbox 305)
## Nexter Project (Grid 305)

### Notes
___
#### **Visual Studio Code**
- **CTRL +D** : Select terms to modify all at the same time

#### **CSS good practices**
- Begin project with the usual * {} for padding and margin to zero **AND** add box-sizing:border-box;
- Put font-family into the body and not into the * selector. 
  
#### **New stuff learned today**
- **Multiple background** (image + gradient/color) : background-image:*gradient*,*image url* ; 
- **clip-path**:polygon (Top Left, Top Right, Bottom Right, Bottom Left); same effect than fusion mask on Photoshop each point takes X and Y coordonate
- Don't use more than 2 properties in keyframes animation (opacity and transform)
- **animation-iteration-count** : x; > repeat X time the animation
- **animation-timing-function** : linear, ease in ease on stuff
- **backface-visibility** : hidden > hack for unwanted animation shake comming from ... who knows ?🤷🏾‍♀️ . To put on the container of animated stuff 
- More than one transform > **transform : transform1() transform2();** no comma
- **.class:link** : link is a state of the button selector
- **all in one animation** : name, animation duration, animation timing function, animation delay;
- **animation-fill-mode** : backwards > Automaticaly apply the styles up to zero percent before the animation starts.
- 