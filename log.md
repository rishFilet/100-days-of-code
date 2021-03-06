# 100 Days Of Code - Log

### Day 1: September 13, 2020

**Today's Progress**: Started doing react in a real world application. Completed a donate Call to Action button with colour animation and confetti using react-dom-confetti

**Thoughts** First time using react and it is very similar to dart, easy to pick up but can be seen hard to master.

**Link(s) to work**
1. [Accelerator Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby/tree/rk/donate_btn)
***

### Day 2: September 15, 2020

**Today's Progress**: Re-started flutter/dart and created a home screen with active buttons and retrieving an image using api

**Thoughts** After leaving flutter for almost a year, i found it alot easier to pick back up given that i understand programming concepts a lot better and able to translate the code and what it is doing. An example is seeing how constructors/intiailisers work. It is easier to figure out the code and cleaner architecture having this experience. This means that the more i practice concpets as opposed to specific syntax, i can learn any language or stack pretty quickly.

**Link(s) to work**
1. [SwipeNSwap](https://github.com/rishFilet/swipe_n_swap.git)
***

### Day 3: September 18, 2020

**Today's Progress**: Worked on fixing the animation for the donate button on TTM website. Fixed layout issues with text, button and heart. Made heart grow with hover over button.

**Thoughts** Animations are very tough in web dev. I have a new respect for how much effort goes into making an animation for a webpage now.

**Link(s) to work**
1. [TTM Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby)
***

### Day 4: September 22, 2020

**Today's Progress**: Worked on fixing the tab accessibility borders on the navbar

**Thoughts** Learned about using windows and event listeners

**Link(s) to work**
1. [TTM Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby/tree/rishfilet/accessibilty_buttons)
***

### Day 5: September 23, 2020

**Today's Progress**: Worked on adding responsiveness to elements 

**Thoughts** Learned about using viewports and an interesting technique in css called calc

**Link(s) to work**
1. [TTM Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby/tree/rishfilet/accessibilty_buttons)
***

### Day 6: September 24, 2020

**Today's Progress**: Added optimisations to make the website load faster by preloading images and not loading the html until the react is loaded. This was done using React Hooks

**Thoughts** React hooks are very powerful and the difference between componentDidMount and effects is that effects can be used in a functio and does not need a class. Preloading fonts, especially ones from a url are better set to load in the cache using a plugin. They can be checked in the network inspector of the website to see which elemnts are taking the longest to load. Preloading and prefetching is important and seeing that things load in a correct order.

**Link(s) to work**
1. [TTM Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby/tree/1/rishfilet/loading_elements_bug)
***

### Day 7: September 25, 2020

**Today's Progress**: Worked more on preloading fonts for other sections of the page, specifically with loading fonts that are using materialUI styling. Still trying to figure out why the logo and skyline header are loaded after the html is loaded causing some breakage 

**Thoughts** Loading fonts is different when using material UI for styling. Adding a placeholder is a good idea (such as a blurred photo) when loading images to give the effect of progressive loading but this does not solve the images not loading when the site first loads up.

**Link(s) to work**
1. [TTM Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby/tree/rishfilet/preloading_images_fonts)
***

### Day 8: September 28, 2020

**Today's Progress**: Worked on setting up an azure pipeline for deploying the android app on committing to master

**Thoughts** : After a lot of effort, there were issues with the quota for the microsoft hosted service and issues with the agent for self hosting. Spending a lot of time debugging was not worth it to commit to using azure devops for this application.

**Link(s) to work**
1. [Swipe n Swap](https://github.com/rishFilet/swipe_n_swap/tree/rishfilet/setup_CI_Android)
***

### Day 9: September 29, 2020

**Today's Progress**: Took a break from the devops and went to making a script on python that can add these logs easily without having to visit github or open an ide.

**Thoughts** : I miss python. So powerful with such small snippets of code. Working on this is making my realise that python may not be the best end result for a UI so might have to transfer to a webapp or API that can be accessed from flutter or email.

**Link(s) to work**
1. [Add to gitlog script](https://github.com/rishFilet/add-to-gitlog)
***
### Day 10: September 30, 2020

**Today's Progress**: Worked on creating the android pipeline using travis CI and fastlane

**Thoughts** : Travis and fastlane seem to work alot better than azure dev ops. There were a lot of issues with devops that could not be overcome easily. Fastlane does have a bit of a setup and learning curve with flutter but works great with travis and easy to connect by just using a yml file and triggers on upload.

**Link(s) to work**
1. [Swipe n Swap](https://github.com/rishFilet/swipe_n_swap/tree/rishfilet/travis_firebase_distribute)
***
### Day 11: October 1, 2020

**Today's Progress**: Worked on fixing loading of the elements and fonts. Learning hwo to optimise the loading of SVGs in react

**Thoughts** : Optimising the loading of SVGs goes a long way to the performance of the website. Doing this also uncovered some areas of the website that take a long time to load. It should be noted that there were differences in performance on chrome and firefox. Using the profiler tool is very powerful to finding these loading issues and which parts take long to load. 

**Link(s) to work**
1. [TTM Website](https://github.com/Toronto-Tech-Mentoring/TTM-Gatsby/tree/rishfilet/preloading_images_fonts)
***
### Day 12: October 2, 2020

**Today's Progress**: Successfully created the pipeline for the android app and conditionally test and build when not on master. 

**Thoughts** : Learned a lot about how to use Travis CI and creating stages and jobs. Found that the errors came down to licesnses, the correct SDK version and checking in the fastile if i am not trying to find a folder that has not existed before the build (i.e. the debug-apk) folder.

**Link(s) to work**
1. [Swipe n Swap](https://github.com/rishFilet/swipe_n_swap/tree/rishfilet/travis_firebase_distribute)
***
