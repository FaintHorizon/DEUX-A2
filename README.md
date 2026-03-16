# DEUX-A2

# Design

# Development

# Testing

# User Stories <br>
User Profile Picutres courtesy of (OpenAI, 2025)<br>
## Profile One:

<img src=".\Images\Profile1.png" alt="Profile One" >

## Profile Two:

<img src=".\Images\Profile2.png" alt="Profile Two" >

## Profile Three

<img src=".\Images\Profile3.png" alt="Profile Three" >

## Design Choices Bassed on Profiles <br>
**Profile One** --> Large High Contrast Text + Dark Mode <br>
**Profile Two** --> Continue Watching Carousel + My List for favouriting shows <br>
**Profile Three** --> Showcase Highlights + Recomendations for binge watching + Autostop <br>
<br>
# Framework
A few things are a constant between all frameworks. One the text is high contrast, two while not present on the form it will be present on the actual site and the other frameworks is all fonts are derived from the Sans family and monobloked for dyslexia friendliness. (Lys Forstner, 2023) This article covers how to desigin news sites to be dyslexia friendly. Along with (W3C, 2025) these are gonna be My main sources for accessiblity and readability.
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
<img src=".\Images\carousel.png" alt="Carousel" >
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
