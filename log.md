# 100 Days Of Code - Log

### Day 0:  Sunday, May 28th, 2017
##### Getting started

**Today's Progress**: Signed up for Twitter account (ugh!), and joined the club at Twitter and Gitter, cloned the repo.  

### Day 1: Monday, May 29th, 2017
#### Day One.
Working on image resizing for carousel by using GIMP to make all images at the same size, adding alpha layer if necessary. Yes, there is method in css where you could fix all images.  However, it reduces load times if you create smaller images and standardize them beforehand.

Learned more about what the breakpoints and Bootstrap's col does exactly.  Gained better understanding of what happens (stretching and breaking into vertical stacking) See the [CodePen](https://codepen.io/pkshreeman/pen/ybdBZa?editors=1000)

Took me a while to realize that I can upload a generic movie file on twitter without having to change it into gif file...Thank god!

Okay, I have added clearfix to some of my div's and I'm not sure whether it is working a hundred percent of time.  I implemented img-responsive class to pictures, and the responsiveness has improved much more.  In addition, I set the divs' heights to be hard coded at min-height for paragraphs in the carousel so it will not bounce around so much.  Unfortunately, if someone add a lengthy summary, it will bounce noticeably.  Removed automatic opening of some of my sections for better presentation.  Added links and one more project to carousel.  

#### Day Two.
I recreated the starting kit for React so that I would be able to deploy my own copy of React-based code.  I also started the process of creating Google Spreadsheet "editor" for workout app purposes.  I then started trying to add background image to SASS without success.

#### Day Three
Successfully added the background image as simple <img> tag in HTML.  Including the background url in the SASS seem to be very bad idea.  There was almost nothing recent on StackOverflow regarding this issue.  I made some opacity adjustments for the paragraphs and text in the HTML after adding the background image. Added "about" page, not even close finishing it, but started something...

#### Day Four
Fixed the HTTPS issue, by ensuring that all the calls are within HTTPS.  The openweathermap did not have https service so I bypassed that by using my own server on https api calls.  
I also finally implemented Timeline.js.  I felt like cheating by using their embedded system, but I realize that there are some things that I should take advantage of, instead of reinventing the wheel every time.

#### Day Five: June 2, 2017
I created a meetup: Roseville-Free-Code-Campers-All-Coders-welcome and 12 new members signed up within two hours!
Anyway, today I spent some time setting up my timeline on my "About" section.  I finally got to create another codepen.io for Bootstrap illustration for multiple column settings.  I am now in process of installing "scroll-to" jQuery fix to my button since it doesn't automatically scroll to the clicked element.  However, now there's another problem.  The user has no idea which one is showing and hiding at the moment, so it can give false start. Another possible to-do list is to add animation to it.  Finished adding "active" addClass/removeClass jQuery with hidden/shown.bs.collapse triggers.

#### Day Six: June 3, 2017
Learned about surge.sh, and how it worked.  Tried to deploy React app on it without building it.  Learning about codepen.io and making my own react website.  

#### Day Seven: June 4, 2017
Learning more React.  Did not make much progress code-wise.

#### Day Eight: June 5, 2017
Completed the Free Code Camp's camper's leaderboard project.

#### Day Nine:  June 6, 2017
It is getting tough.  I am running out of ideas to write, and am not motivated to complete the FCC projects.

#### Day Ten: June 7, 2017
Working on P1xt's challenge!  Very educational in respect to how much details plays into the final product.  So many things to do... Couldn't figure out parallax yet,  and have not started javascript yet as the 1/3 to 1/4 of the front-end is not complete yet.

#### Day 11: June 8, 2017
Updated my personal portfolio for paragraph to be more visible.  Worked on GIMP for better image sizing. So close so far away.  Zooming for hover works now.  Video with cover image isn't working the way I want it.  Added selectors for images.

#### Day 12: June 9, 2017
Finally finished the P1xt's challenge.  The headers font was causing so much problems when testing for responsiveness.  

#### Day13: June 10, 2017
Worked on Canvas HTML5 to see if I can refactor my Simon Game using that.

#### Day 14: June 11, 2017
Continued to work on the Canvas HTML5 in Simon Game refactoring project.

#### Day 15: June, 12 2017
managed to render image of simon using html5 canvas!  Now, the next stage: interactivity....

#### Day 16: June 13, 2017
Added onClick bindings to canvas with functions.  Small steps, smalls steps.

#### Day 17: June 14, 2017
Binding 'this' to canvas.  Found out that I can't use 'this' inside a const outside of constructor.  Would have been nice to know that beforehand, and have better access to console.  CodePen isn't great tool for debugging these things.  Seriously considering going over to 'createReact' path.

#### Day 18: June 15, 2017
Testing the limits of what is passable to props in React.  Created customized React for testing in stackoverflow: <https://codepen.io/pkshreeman/pen/GENmaG?editors=0010>

#### Day 19: June 16, 2017
After having trouble debugging the React app in Simon refractor project, I decided to go ahead and create create-react-app locally, and try to run it from there.

#### Day 20: June 17, 2017
Successfully fixed the persistent bug.  Forgot to include 'return' in the function.  You'd think I'd know better...Now I have a functional prop-non-logical simon operational.  Time to incorporate the states.  Did not want to add logic until after the state is installed.

#### Day 21: June 18, 2017
Slow but steady progress with logic setup in Simon game.  Losing motivation for some reason.  

#### DAY 22: June 19, 2017 Monday
Still slow progress with logic.  Managed to do cool things with calling 'this' via functions.  Learned I can call function inside setState due to its async nature.

#### Day 23:  June 20, 2017 Tuesday
Async operations of setState is causing major headaches in logic functions.

#### Day 24: June 21, 2017 Wednesday
Was unable to make the demo (showing the sequence) to work correctly due to async calling of canvas (or is it necessary to clear the canvas? )

#### Day 25: June 22, 2017 Thursday
Insight:  SetTimeOut != SetInteval because SetTimeOuts does not prevent overlapping of async operations.

#### Day 26: June 23, 2017 Friday
shreeman-simon.surge.sh
Let's see if I finally can deploy a completed React based Simon Game.

#### Day 27: June 24, 2017 Saturday
Unhappy to find out that Simon Game is not being correctly emulated on mobile phone. >:(

#### Day 28: June 25, 2017 Sunday
Lot of reading and research.  Django with Python, Xcode tutorials, research local storage procedures for next project.

#### Day 29: June 26, 2017 Monday
Django...

#### Day 30: June 27, 2017 Tuesday
Lot of figuring out about using python 2.7, 3.6 in what kind of env.  Virtualenv configurations, vagrant configurations, mysql setup in vagrant, and running basic test website in django via vagrant porting.

#### Day 31: June 28, 2017 Wednesday
Started recipe box for FCC project.  React.js is still extremely painful to write.

#### Day 32: June 30, 2017 Friday
Skipped a day to focus on self-analysis and development.  Learned and worked on Typescript today.

#### Day 33: July 1, 2017 Saturday
Worked on Swift in Xcode using tutorials.  Had to start over from stratch since there was some type of errors that can't be resolved.  it is working now...sigh...

#### Day 34: July 3, 2017 Monday
Yes, Skipped a day again.  It is getting hard to be consistent since I do not have an ongoing steady project.  I have tons of things I want to learn but it spreads me out thin. I did some work on FCC's recipe program using react/sass.

#### Day 35:  July 4, 2017 Tuesday
Seems I am having tough time staying consistent with the programming.  Need to pick one project and stay with it.  I think I have too many projects, and spreading myself out too thin.  Suspending FCC Recipe project as I need to work on 'real' projects as actual deployment of django website, developing actual application for iOS.  Seems that is more 'important', than struggling with details of react project (as how to use local storage in JSON format and successfully list it out in a human readable format.)  For today, I am focusing on swift/iOS development toward augmented reality.

#### Day 36: July 5, 2017 Wednesday

Working on React project.  Why is JSON such a pain to use?  I have used JSON many times, and it is still major headache to handle it.  I must be weak in javascript if I always have this problem! 

#### Day 37: July 6, 2017 Thursday

Worked all day on learning how to deploy Django to Heroku.  Finally figured out the localhost vs deployed issue in relation to using postgreSQL, and updated the code, and created a [pull](https://github.com/heroku/python-getting-started/pull/32)

#### Day 38: July 7, 2017 Friday

Implemented Workout App.  Phase 1 :D

#### Day 39: July 8, 2017 Saturday

Phase 1....and not 2 :( 

#### Day 40: July 9 2017 Sunday
I dropped a table in Django...big mistake.  Now removed entire folder to start over,  learning firsthand how useful venv and install pip -r requirements.txt can be now...

#### Day 41: July 10, 2017 Monday
Working on Workout App Django-Heroku implementation.  DB issues being worked on with the rest of project from ground zero...

#### Day 42: July 11, 2017 Tuesday
Went over to Django's 1.11 tutorial to figure out the POST-Database relationship and started working from the tutorial.

#### Day 43: July 13, 2017 Thursday
Finally successfuly setup the database using POST data.

#### Day 44: July 14, 2017 Friday
Learning more about UI for phone vs computer...and fixed database for missing reps.