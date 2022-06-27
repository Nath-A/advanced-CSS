# Advanced CSS
From [Udemy - Advanced CSS and Sass Flexbox, Grid, Animations and More!](https://www.udemy.com/course/advanced-css-and-sass/)

## Natours project
[Natours - WIP](https://nathalie-anneessens.github.io/advanced-CSS/Natours)
<!-- **TODO**
- [ ] Change units from PS to REM and add  -->

### Passe 1 - CSS
- [x] Header HTML + CSS
- [x] Header CSS better practices
- [X] Header implement BEM
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
- Begin project with the usual *, *::before, *::after {} for padding and margin to zero **AND** add box-sizing:inherit; + body {box-sizing:border-box;} 
- Put font-family into the body and not into the * selector.
- **CSS Termonology**
  ![CSS Terminology](readme/css-terminology.JPG)
- **Using REM instead of px for lenght units** to simplify responsive design > put **html {font-size:~~10px~~ 62.5%;}** ( % to not overwrite the browser parameters written by the user) to html selector
- When we have a point, don't write the 0 > ~~0.5rem~~ > **.5**rem
  
#### **New stuff learned right now**
- **Multiple background** (image + gradient/color) : background-image:*gradient*,*image url* ; 
- **clip-path**:polygon (Top Left, Top Right, Bottom Right, Bottom Left); same effect than fusion mask on Photoshop each point takes X and Y coordonate
- Don't use more than 2 properties in keyframes animation (opacity and transform)
- **animation-iteration-count** : x; > repeat X time the animation
- **animation-timing-function** : linear, ease in ease on stuff
- **backface-visibility** : hidden > hack for unwanted animation shake comming from ... who knows ?🤷🏾‍♀️ . To put on the container of animated stuff 
- More than one transform > **transform : transform1() transform2();** no comma
- **.class:link** : link is a state of the button selector. Best practice to use **a:link** also
- **all in one animation** : name, animation duration, animation timing function, animation delay;
- **animation-fill-mode** : backwards > Automaticaly apply the styles up to zero percent before the animation starts.
- **Units conversions**
![Units conversion](readme/units-conversion.JPG)
- **Box model** : Fill area = content + padding + border (area that gets filled with background color or background image)
- **Box-sizing:border-box**
![Box sizing : border-box](readme/box-sizing_border-box.JPG)
  Dimensions will be for the entire fill area, not just for the content area
- **Component-driven design**
  ![Component-driven design](/readme/Component-driven-design.JPG)
- **BEM**
  ![Block Element Modifier](/readme/BEM.JPG)
- **Architecture folders : 7-1 pattern**
  ![7-1 pattern](/readme/7-1-pattern.JPG)
  - base : basic product definitions [???]
  - components : one file for each component
  - layout folder : to define the overall layout of the project
  - pages : style for specific pages of the project
  - themes : if we use different visual themes
  - abstracts : no css, but variables or mixins
  - vendors : where all third part CSS goes
- **Comments in SASS** //comment
- **Nesting**
- ![Nesting](/readme/nesting.JPG)

- **Mixin** : reusable piece of code > @mixin name {}
  ![Mixin & argument](/readme/mixin-argument.JPG)
  ![Mixin & argument](/readme/mixin-argument-include.JPG)
- **Placeholder and extend** : for elements who looks almost exactly alike 
  ![Placeholder & extends](/readme/placeholder-extend.JPG)
- **Command line ls** are not working on windows. Instead use "dir"