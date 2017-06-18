# grid_painting
I'm 'painting' with CSS a water-color(?) as a project to help me learn Grid.
CSS shapes may need to come into play here as well.

### Here's the painting. It seems ideal for grid (line-based approach);
[![step1](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/original.jpg?raw=true)](https://codepen.io/beau_dev/full/dRXpZX/)



#### An outline in order to prepare definition of grids:
[![step1](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/outline.png?raw=true)](https://codepen.io/beau_dev/full/dRXpZX/)





#### And here's step 1.
![step one](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step1.png?raw=true)


Grid columns have greek names.
& rows will have A-Z names for now (at least for the outer map).

Doesn't look like much now, but it has potential...
434px
36px
34px
12px
6px
64px
20px
28px
114px
#### And here's step 2.
![step one](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step2.png?raw=true)
Going to be harder than I thought. This is a first pass on Epsilon. CSS Shapes is going to have to come into play here. Oi vey. That box-shadow on the roof needs alpha adjustment. Or I could hide z-index/position abs a bordor-radiased circle and shadow that puppy for a rounder shadow...(?). Ugh... Why did I start this? --Now I can't stop.

I may try to change every px value to fr in order to make it responsive.

#### And here's step 3.
![step three](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step3.png?raw=true)

Need to rename elements semantically.
Need to learn "subgrid" property in CSS grid.
Need to remember that z-indexing will be done and not to render house facades as they appear on the page. z-indexed layers of linear-gradient black to opacity will do this for me.

Grid is coming easier now.
lots of counting pixels.
slicing up image sections is helping
![image slice](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/darkhouse.jpg?raw=true)

FIXME: SASS!

Day (what? 5?) Ugh...this is slow. :(

  --BUT SO MUCH FUN!

The project is now officially subdivided and modularized is sass! :)

It was about 30minutes, but it was fun. --Totally helpful to reinforce my grasp of the behavior of sass --watch and it's vicissitudes.

#### And here's step four.
![step four](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step4.png?raw=true)

#### And here's step five.
![step five](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step5.png?raw=true)
discovering the power of linear-gradients at an angle.
Having trouble centering the entire.
Subdivided entire thing into modular bits of code semantically mirroring what is rendered in the browser.

#### Step 6.
![step Six](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step6.jpg?raw=true)
This is a kind of madness.
Rendered bricks on brick house with "IIIIIII" forever in a ::before tag and then I'm using jQuery to add a class to divs.
< div >eloper status: confirmed. :(
I used polygon clipping and rotation for the white-house roof at the top-left corner. In firefox, though, there's different behavior. z-indexing, by design, is implemented differently.
https://stackoverflow.com/questions/31646746/z-index-behaviour-is-different-in-chrome-to-firefox

If this works in codepen, it'll be a miracle.

I also used "clippy" http://bennettfeely.com/clippy/ to test the shape.

ok... I'm going to bed. It doesn't look like much now... but Kaizen...Kaizen...Kaizen.
I have to admit (and I'll probably delete this later) --At 3am, detailing the angles and opacities in a radial gradient... I wonder what the hell I'm doing with my life. :/
#### Step 7.
![step Seven](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step7.png?raw=true)
Okay. I'm beginning to obsess. It's the tiny whisps of shadow that bring this to life. Had I taken a drawing class I would've discovered this years ago.
Okay. Tonight we did lots of grid and some fooling with positioning. I STILL am not entirely certain I'm doing it right.
Best discovery is the steps and the peach-house left chimney. linear-gradient percentages simulate the element receiving shadow. SO MUCH frikkin' fun! (can I swear on Git?).

By the way, my SASS files are no where near as clean as they could be.

I learned a bit of architecture today. The mansard roof --or "the French Roof". New Orleans... makes sense.

Alright--enough of this craziness. I'm going to bed.
