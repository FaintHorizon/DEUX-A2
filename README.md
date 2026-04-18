# DEUX-A2
# Table of Contents
[Design](#design)</br>
----[Aims and Objectives](#aims-and-objectives)</br>
----[User Design](#user-design)</br>
----[Wireframe Adjustments](#wireframe-adjustments)</br>
[Development](#designevelopment)</br>
----[Development Screenshots](#website-screenshots)<br>
----[Development Reflections and Design Challanges](#development-reflection-and-design-challenges)<br>
[Testing](#testing)</br>
----[Lighthouse](#google-lighthouse)
----[Manual](#my-testing)
----[W3CAG](#w3-html-and-css-validation)
[User Stories](#user-stories)</br>
----[Profile One](#profile-one)</br>
----[Profile Two](#profile-two)</br>
----[Profile Three](#profile-three)</br>
[Frameworks](#framework)</br>
[Reference](#references)</br>
# Design
## Aims and objectives
The primary aim of the site was a highly accesible and usable online streaming service. Delivering information cleanly and with high contrast and customisatoion
- The site had to be reponsive
- The layout and theme had to be consitant
- Accessibility options had to be taken into account.
- It had to load at a somewhat ok pace
## User Design
**Profile One** --> Large High Contrast Text + Dark Mode + Subtitles<br>
**Profile Two** --> Continue Watching Carousel + My List for favouriting shows <br>
**Profile Three** --> Showcase Highlights + Recomendations for binge watching + Autostop <br>

## Wireframe adjustments
The wireframes I initialy developed inflated the scope of the project drasticaly and impracticaly given the time scale so I am goint to only do three of the ones shown bellow .<br>

### Wireframe One 
The first page you load onto is the signup page this is what i am using as my form it has a nice dark mode, high contrast text and examples of what you need to input for each box.

###  Wireframe Two

The second page you hit after the signup page is the main page where all your media is.</br>
- This has a high contrast navigation bar up top.</br>
- A clearly displayed showcase piece
- And a continue watching section

Come full deployment this would be expanded to be a much longer scroll with suggested cataories following the same design principle of the continue watching.

### Wireframe Three

The final wireframe is the attempt at the video player. On the framework the </br>
- Subtitles
- Playback bar
- Backbutton
- Media Title

Are all high contrast and stand out nicely.

# Development
## Website Screenshots
###  Signup
<img src=".\Images\websiteSignup.png" alt="Website Signup"><br>
<br>

### Main Page
<img src=".\Images\websiteMainpage.png" alt="Website Main Page"><br>
<br>

### Media Player
<img src=".\Images\websiteVideoplayer.png" alt="Website Media Player"><br>
<br>

### Media Player
<img src=".\Images\websiteTBB.png" alt="Website Under Construction"><br>
<br>

## Development Reflection And Design Challenges

Pages Deployment: https://fainthorizon.github.io/DEUX-A2/<br>
<br>

Using Bootstrap, W3Schools and a bit of ChatGPT to help teach techniques a few issues for teh development quickly arose.
Other Tools used include:
- Affinity Photo for Wireframes and images
- Davinchi Resolve for video editing
- Bambu Studio for the 3d print timelapes
- Visual Studio for coding
- Github for version control and syncing
- Github Pages for deployment

- With no backend a few things where off the table for development like;
    - Due to no backend continue watching was of the table
    - Without the backend and a extensive media collection things like recomended films/tvshows would be near imposible to do
- The final issue is the subtitles in the media player while i explored approches such as using Youtubes API but I didnt want to have to rely on an external service for a media player. In full development a more indepth media player will have to be built that would hook into a backend subtitle database for the different media. Then the more extensive customisation options can be built ontop of that.

Unfortunatly thouse issues hit most of the user requirements.

With Bootstraps reactive web design the challange of having the site auto format to a device became a lot easier just had to be cautious about some images giving them a max hight/width to make sure they dont overwhelm the UI



# Testing
## Google Lighthouse
### Signup Page
<img src=".\Images\lighthouseSignup.png" alt="Lighthouse Signup Summary"><br>
With  the simplicity of the Sign up page it scored well on Lighthouse with its main points lost as i used uncompressed high quallity images for parts like the logo


### Main Page
<img src=".\Images\lighthouseMain.png" alt="Lighthouse Main Summary"><br>
It loses points for accessibility as I didnt give alt names to the buttons
Points in search engine as I didnt describe where the links went
And performance as again I have lots of high quallity images

### Media Page
<img src=".\Images\lighthouseMedia.png" alt="Lighthouse Media Summary"><br>
Due to simplicity media agains scores very highly as there is very little going on the actual page

### Construction Page
<img src=".\Images\lighthouseTBB.png" alt="Lighthouse Construction Page"><br>
Due to simplicity media agains scores very highly as there is very little going on the actual page

## My Testing

Clicking through all the buttons seemed to lead to the correct places for stuff that was not included in development it lead to a construction page, the form lead to the main page, the back button from media lead to main and the HTML video player works.

Images loading correctly and in deacent time 

The website is responsive to differnet aspect ratios and resolutions through chromes inspect feature

The Main remaining issues where discused in development some due to lack of a backend and then subtitles.

Userstories that where implemented where A dark mode, high contrast
Dark mode is present throughout the theme and the contrast check is availble near the bottom of the framework section getting scores of 21:1 and 19.02:1 both in the WCAG AAA catagories for contrast

## W3 HTML and CSS validation
### HTML
<img src=".\Images\W3HTMLVal1.png" alt="W3 HTML Validation"><br>
<img src=".\Images\W3HTMLVal2.png" alt="W3 HTML Validation"><br>
<img src=".\Images\W3HTMLVal3.png" alt="W3 HTML Validation"><br>
<img src=".\Images\W3HTMLVal4.png" alt="W3 HTML Validation"><br>

### CSS
<img src=".\Images\W3CSSVal.png" alt="W3 CSS Validation"><br>

A lot of errors where picked up during CSS validation but from what i can tell looking through the full report they seem to all be related to bootstrap


# User Stories <br>
User Profile Picutres courtesy of (OpenAI, 2025)<br>
## Profile One:

<img src=".\Images\Profile1.png" alt="Profile One" >

## Profile Two:

<img src=".\Images\Profile2.png" alt="Profile Two" >

## Profile Three

<img src=".\Images\Profile3.png" alt="Profile Three" >


<br>

# Framework

A few things are a constant between all frameworks. One the text is high contrast, two while not present on the form it will be present on the actual site and the other frameworks is all fonts are derived from the Sans family and monoblocked for dyslexia friendliness. (Lys Forstner, 2023) This article covers how to desigin news sites to be dyslexia friendly. Along with (W3C, 2025) these are gonna be My main sources for accessiblity and readability.
<img src=".\Images\DEUXFormFramework.png" alt="Signup Form" >
The form has each box contrasted from the background with and example of what text to supply, when text does not meet the requirements the form should prompt an error messege bellow the box to tell the user what they did incorrectly. An example of which is bellow.
<img src=".\Images\BadForm.png" alt="Bad Form" >
As you can see when the user enters a result into the form, A, Their text turns white to clearly differenitate from suggestions and B, when the form fails it places a red error message bellow to inform the user what they did wrong. Like most parts of this site it should be possible to navigate with tab movement.

The Main Page of the site has a few elements. It features a navigation bar at the top allowing the user to browse by catagory, film or tv show or browse content they have previously put into a list this links back to our user stories of allowing users to easily catch up on shows they want to watch.  
It also has a search button and access to account settings following the Z pattern with the user first looking at the navigation bar, then the search area before moving onto the main content.
<br>  
The suggested contents which can either be a sponserd show or suggested for the user to watch next with two boxes a play now button and more info. If the user is not intrested in the promoted/suggested content they continue to move down into the continue watching list, if they are a new user this will be replaced with a reacently added list.
<img src=".\Images\MainPageFramework.png" alt="Main Page" >
Clicking on a show title will bring them to the media preview page the same as the more info button from here they can play it, add to list or back out if they are not intrested. 
<img src=".\Images\MediaPreview.png" alt="Media Preview" >
If the user presses play they will end up in the media player for whatever content they accessed. In the media preview to keep in line with our user stories we have extensive options for customising subtitles.
<img src=".\Images\VideoPlayerFramework.png" alt="Video Player">
If the player detects inactivity, no volume change, no pausing etc after a set amount of time it will stop playback and bring up the Are you still watching screen.
<img src=".\Images\AreYouThere.png" alt="Are you still watching" >
This screen will allow the user to continue without interuption, continue while just reseting the inactivity timer, or backout the the main page.

On the main page if the user where to scroll down they will end up with the media carousel. This is where we reckon most users will be browsing it will suggest different catagories orderd by what an algorithm determins the user mostlikely to want to watch bassed on their previous watch history. They will be able to flick through a set amount of films in each catagory again the ones we promote to the user.
<img src=".\Images\Carousel.png" alt="Carousel" >
If the user still cannot find what they want to watch or they are trying to find something specific they can turn to the search bar. This will have a Fuzzy search implemented allowing for people to be able to find content if they are not 100% on the spelling. They will also be able to search by cast and catagory.
<img src=".\Images\SearchPageFramework.png" alt="Search" >
As with the carousel and the main page all media thumbnails displayed here will have the title displayed bellow them to assist thouse with visual imparements making a high contrast easy to read title.

As for colour scheme we have gone for a darker scheme by defualt as that helps with more light controled enviroments for flashing the user as they head back to the menu but we will most likely have a light mode availble if a user wants it.  in the dark scheme our contrast varys from an 19.02:1 ratio and a 21:1 ratio due to the background gradient in the dark scheme both of the values pass AAA WCAG guidelines. (W3C, 2025) You can see the results bellow thanks to (WebAIM, 2025).

<img src=".\Images\WhiteOnBlack.png" alt="Contrast 1" >
<img src=".\Images\WhiteOnRed.png" alt="Contrast 2" >

For the light mode we could invert most of these colours but for most users that may apear a little bright
<img src=".\Images\BadFormLight.png" alt="Bad Form Light" >
As an example for what the lightmode could look light
of course black text on white will have the same contrast as white on black of 21:1 but the bright red on white has a contrast of 5.88:1 Which still aligns with AA rating but loses its tripple for normal sized text.
<img src=".\Images\RedOnWhite.png" alt="Contrast 3" >

# References

# Credits
Frameworks made with Affinity Photo and Designer
Alot of code w3Schools for bootstrap, HTML, CSS support
