# grid_painting
I'm 'painting' with CSS a water-color(?) as a project to help me learn Grid.
CSS shapes may need to come into play here as well.

### Here's the painting. It seems ideal for grid (line-based approach);
[![step1](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/original.jpg?raw=true)](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/original.jpg?raw=true)

It was done by Louisiana native, Jim Blanchard.

He's  a prominent architectural archival painter [http://www.jimblanchardgallery.com/](http://www.jimblanchardgallery.com/)

His work is beyond phenomenal and extremely precise.

#### An outline in order to prepare definition of grids:
[![step1](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/outline.png?raw=true)](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/outline.png?raw=true)





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


Day (what? 5?) Ugh...this is slow. :(

  --BUT SO MUCH FUN!

The project is now officially subdivided and modularized into sass! :)

--Oops! --It turns out there ISN'T a "subgrid" property in grid. lol --Was tempted to erase the entry above... but left that silly comment up there. #noob

It was about 30minutes, but it was fun. --Totally helpful to reinforce my grasp of the behavior of sass --watch and it's vicissitudes.

#### And here's step four.
![step four](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step4.png?raw=true)

#### And here's step five.
![step five](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step5.png?raw=true)
Discovering the power of linear-gradients at an angle.
Having trouble centering the entire.
Subdivided entire thing into modular bits of code semantically mirroring what is rendered in the browser.

#### Step 6.
![step Six](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step6.jpg?raw=true)
Alright, this is a kind of madness.
Rendered bricks on brick house with "IIIIIII" forever in a ::before tag and then I'm using jQuery to add a class to divs.

"< Div >eloper" status: confirmed. :(

I used polygon clipping and rotation for the white-house roof at the top-left corner. In firefox, though, there's different behavior. z-indexing, by design, is implemented differently.
https://stackoverflow.com/questions/31646746/z-index-behaviour-is-different-in-chrome-to-firefox

If this works in codepen, it'll be a miracle.

I also used "clippy" http://bennettfeely.com/clippy/ to test the shape.

ok... I'm going to bed. It doesn't look like much now... but Kaizen...Kaizen...Kaizen.
I have to admit (and I'll probably delete this later, but) --At 4am, detailing the angles and opacities in a radial gradient... I begin to wonder what the hell I'm doing with my life. :/

#### Step 7.
![step Seven](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step7.png?raw=true)
Okay. I'm beginning to obsess. It's the tiny whisps of shadow that bring this to life. Had I taken a drawing class I would've discovered this years ago.

Tonight we did lots of grid and some fooling with positioning. I STILL am not entirely certain I'm doing it right.
Best discovery is the steps and the peach-house left chimney. Linear-gradient percentages simulate the element receiving shadow. SO MUCH frikkin' fun! (can I swear on Git?).

By the way, my SASS files are no where near as clean as they could be.

I learned a bit of architecture today. The mansard roof --or "the French Roof". New Orleans... makes sense.

Alright--enough of this craziness. I'm going to bed.

### June 18th.
It's been 7 days. Making progress.

There's an oddity in safari and chrome:
Using filter: blur(); where, (zoomed in) an artifact appears that looks like the grey outline of a pill with an alpha val of .5.
Weird...
Firefox is fine.
![Pill Arifact](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/pill.png?raw=true)


#### Step 8.
![step Eight](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step8.png?raw=true)
It's a good update. I am really gathering some affection for CSS grid. Something is wrong with me.

It's so simple...--But I'm using a fraction of what it has to offer. (#gridnerdpun)

I've run into trouble with linear gradients on borders. If I continue to have this trouble. To hell with it. I'll go with 1px lines.

I'm most pleased with the chiaroscuro. --Here's hoping I don't have to use it too much. #perfmatters

There are issues, however, with the positioning of bits of the top-right of white house. and left side of darkhouse overlapping.

God, this artist must be slightly insane to paint these. They are all incredible. --This is a simple one.

#### Step 9.
![step Nine](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step9.jpg?raw=true)

I'm considering doing doors and windows in SVG. I might mix it up. If you look at the original pic, you'll see wavy shadows of window pane frames on curtains. I've always wanted to try it.

Anyway... We've made lots of progress. :)

P.S.
Wow. I had no idea how long mere maintenance of a project like this would take. I took 3.5 hours to find a positioning problem. --The solution was the "IIIII" bricks "hack" I'm using to create the texture in the brick building. Ugh.
I'm exhausted.

#### Step 10.
![step Ten](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step10.png?raw=true)

Progresssss izzzz slow... But here we are, ten (10!!?!?) days later. ☹️
--I'm not complaining... I'm pleased with the results.

#### Step 11.
![step eleven](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step11.png?raw=true)
SVG clip-path done. Finally, it took hours to figure out--drawing by hand in the browser. #OldSchool -- 'cuz that's just how I roll, yo...

Ugh... Okay that's it I'm going to bed. SVG clip-path to render shadows on the roof.

Lots of color adjustments...and lots of grid stuff done today. I've got 9 days 'till the (false) deadline. :)

To be honest, I think the clip-path looks a bit too slick. I couldn't manage (yet) to figure out how to apply filter to a css image.

If it gets desperate, I'll do it in illustrator and examine the code.
God, I hope this is worth it. I wanna put it down and get on with my life.

#### Step 12.
![step Twelve](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step12.png?raw=true)
Time consuming. It's nice, but I don't think i'm going to submit this.

#### Step 13.
![step Thirteen](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step13.png?raw=true)
Ugh... Don't ask.
Total pain in the butt.

So much fun, tho.

#### Step 20.
![step Twenty](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step20.png?raw=true)
I think I'm really losing it. I used to wonder why I didn't see much drawing with CSS on the net. Now, I understand why... It's because people have lives to live.

It looks great, but... still so much to do.

Tomorrow, the gutters.

#### Step 22.
![step Twenty-two](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step22.png?raw=true)
Ok. It seems like it might have potential, but I don't think I'll be done with this for another few weeks. I've got animation to do & I just don't have enough time. Oh, well...

I must decide whether to individually color each shutter and panel at the expense of the DOM and browser...or just go for it & see what I can do to improve it by refactoring my SASS.

I've been putting off the hardest parts... The rails... I have to go over how to do repeated patterns in illustrator. Ugh... I kind of dread it. I don't want to screw things up.

Doing the mansard roof trim on either side was a big PITA. Was unsure about where to anchor the pieces and use positioning.
ok... Lots to do.
curtains, Doors, etc. Let's get to it.

#### Step 23.
![step Twenty-three](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step23.png?raw=true)

I'm in the home stretch. It's a proof-of-concept.

The SVG was way easier than I thought it would be.

I added a slight ghost of an outline of bricks for the peach house. I've discovered that using text and a million divs for the brick outlines for the brick house with the pseudo-class ::before was a stupid idea. Really inefficient and a hack. SVG will ease some of the burden on the browser.

I have lots of shadows to do and have realized that the shadow above the brick house (as an SVG clipping mask) was also a silly way to approach the problem.
Solution: Simply place an opacity .5(?) svg on top of teh roof! --why didn't I think of that?

Anyway... I will do that for the many, many remaining long shadows that I have to place on each house.

I have "polluted" the html with a great deal of SVG.

But that is an issue to solve for another day.

However, to be frank... it all looks a bit too "crisp" and clean for my taste. There is no sense of atmosphere. --No gauzy, particulate leaves blowing or blur... It needs something!


#### Step 24.
![step Twenty-four](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step24.png?raw=true)

Okay. Well... This frikkin thing took 4 hours. I'm still learning illustrator. I didn't want to pollute the DOM with too much SVG and instead of a linear gradient from the top right to depict shadow, I did that in the CSS background (containing) div and put an opacity 50% in illustrator for the columns. I have four days left. --It's still just static. I like what I see, but there's so much incomplete about this.

I have had very little sleep in the past few days & it looks like I'm not going to get much this week.

I often wake up in a panic thinking about what is broken.

It really is absolute madness.

okay... on to more of this... I'm going to take on the house all the way to the right. The "short-house".


#### Step 27.
![step27](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/step27.png?raw=true)

I need to put the gutterpipes on each building. It's looking a bit empty and I shold pay closer attention to the original painting as a guide.

I'm happy with it, though.


#### Step laststep.
![last step](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/laststep.png?raw=true)
Submitted at 5pm yesterday.

I learned lots in this past month.

Things I would do over if I had the time:

The clouds. I thought they this pic needed something in the background and I overdid it. This could be solved with an opacity adjustment. --or a size adjustment.

My friend said, "I expected Snoopy to jump out of the sky!" ... LOL... Point taken.

 --I should take that lump and learn from it. It was a friendly, funny criticism and he has a point.

I most regret that logo (center pic above) doesn't work on all screens.

Even in chrome... on some resolutions it doesn't quite work.

It's a "works on my machine" problem and very approachable and solvable.

I concentrated on chrome and firefox--but neglected to test in safari. --It looks awful on safari.

I started too late on the final logo & still don't quite understand the svg sizing and viewBox concept. It's a basic concept and I should know better.

Things I did properly:

I edited the song at a particular point to remove the solo. I did this in AE of all things. It's the only editing program I know--But it was a coup to do this & greatly improved the over-all timing and visceral feeling that the animation gives.

Above all, I'm very pleased with how the SVG integrates with the css. The key is proper, painstaking attention to shades of color. --Otherwise the gutterpipes and the door of the peach house would look comical. I really wanted to avoid that.

#### Step result.
![last step](https://github.com/Beauvelop/grid_painting/blob/master/public/steps/result.png?raw=true)

Okay. It's done.

If anyone ever reads this. I'd like to thank you for reading. Give a little love to a newbie on twitter @beau_dev

Thank you!

The final. :)

https://codepen.io/beau_dev/full/rwZPjm/

Please watch in full-scrn :)
