<h1> The Monkees  </h1>


<b>One or two paragraphs providing an overview of your project</b>.

In this, the first milestone project, I will implementing what I have learned and what I can do at this early stage of my coding career. 
For this project I had loads of ideas:
<ul>
<li>A live news feed for the <b>Index</b> page </li>
<li>Links to the bands Spotify/youtube/twitter/facebook on every footer</li> 
<li>Album playlists that changed the song list when clicked on the shopping page</li> 
<li>Monthly news letter subscription</li>
<li>different payment options</li>
<li>audio sampling of songs</li>
<li>online shop with constantly updating merchandise</li>
<li>Automatic update on home page if a new item has added</li>
<li>notice appearing on the top of the home page that all first time orders have an instant 33% discount</li>
<li>Monkees TV show episodes/ clips from the show</li>
</ul>

<p>After careful consideration I have decided on several features to include for the opening versions of my project and what can be implemented for the future versions.</p>

<p>For the initial version of my project I have implemented a news section in the Index page, right now it is filled with Lorem text as to give the band an idea as to what it is going to look like.
from the limited library that I must hand. I was able to get a few of the songs and album covers implemented into the tunes section. Each of the songs has an excerpt from wikipeda beside it to 
give the user a glimpse into the history of the piece, beside what we have, as the main attraction the music video of Daydream Believer.

<b>UX</b>

<p> My UX process is a pretty simple one. I start with my end goal and work backwords taking each step as a stepping stone to reach how I should start my project as explained above. 
My aim was to provide an avenue for fans of the band, long term and new fans, to find out something they didn’t previously know about the band. Whether that is through our news feature or through the stories in tunes we always have something to offer.


My focus for the site is to keep the user's attention engaged. this is done in several ways. First of all, we need an eye catching story to put on the front page There is also an embed link to Youtube and Spotify Widgets to a couple of albums from the band. </p>

What I aim to achieve:

<b>Jimmy:</b>


"as somebody that was born long after the rise of the monkees, I wanted to get to know what the bad was like what sort of music they are making, what the tv show was like, so I naturally gravitated towards the site, 
It has all the information i need, as well as a music, music videos, stories from behind the scenes and more!"

<b>Tommy:</b>


"I grew up listening to the monkees on the radio and watching them on the tv. I have followed their career from the first comedic musical beginnings in 1966 until today. The website keeps me updates with everything that is going on today."

<b>Julie:</b>

"I am an avid collector of music and music memorabilia. I have Such a soft spot for all things Monkee related. The news letter keeps me up-to-date with sales happening in the store and when there is anything new, I can add to my collection "

These are the 3 core user types that I bases my site around, from my <a href="assets/Wireframes/Band website mockup.bmpr">wireframes</a> as a starting point to the stories on the stories on the <a href="tunes.html">Tunes</a> page to the music and Merchandise that will be available on the <a href="shop.html">Shop</a> page

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

As part of this section we recommend that you provide a list of User Stories, with the following general structure:


In addition, my plans for the future of this website is to:

<ul>

<li>Have either clips or full episode on the monkees tv show</li>
<li>Have a shop with customisable merchandise page i.e. names birthday customisable signed merchandise </li>
<li>Run monthly competitions to receive signed merchandise</li>
<li>Set up a Monthly News letter called "Monkee Around Monthly"</li>

</ul>


Technologies Used

Once I took stock of all the technologies used for my project, I was genuinely surprise at the ever growing list that I amassed. 

<ul>

<li>HTML 5 for the basic lay out and structure of the site</li>
<li>CSS for the colour and style of the site </li>
<li>Google fonts for the style of the writing in the site <a target = 'blank'href="https://fonts.googleapis.com/css?family=Chicle"> Google Fonts</a></li>
<li>Font Awesome for the small stylised icons (facebook, twitter, spotify icons) <a target = 'blank'href="https://fontawesome.com">Font Awesome</a></li>
<li>Hover for the hover effects when navigating <a target = 'blank'href="https://cdnjs.com/libraries/hover.css">CDNJS</a></li>
<li>Bootstrap for the navigation button style <a target = 'blank'href="https://getbootstrap.com/https://getbootstrap.com/">Bootstrap</a></li>
<li>Jquerry as Bootstrap relays on it <a target = 'blank'href="https://jquery.com">Jquery</a></li>
<li>I used a lot of the information on the Code Institute course along with all of the music and pictures of the band <a target = 'blank'href="https://codeinstitute.net/">Code Institute</a></li>
<li>LinkedIn learning fort the responsive Iframe for the music video <a target = 'blank' href="https://www.linkedin.com/learning/">LinkedIn Learning</a></li>
<li>All of the information I used regarding the Bios and stories surrounding the music was taken from <a target = 'blank'href="https://en.wikipedia.org/wiki/Main_Page">Wikipedia</a></li>
<li>EmailJS to send and receive emails via the contact page <a target = 'blank'href="https://www.emailjs.com/">EmailJS</a></li>.
<li>I used spotify widgets for the playlists in tunes <a target = 'blank'href="https://www.spotify.com/">Spotify</a></li>
</u>

<h2>Testing</h2>

<p>My approach to testing was a break it as you go type of approach. I would make a feature and test what I would need to do un render the site unusable. so, for example on index.html. I had a lot of issues with the navigation buttons and the images at the top of the page. The images remained the same size no matter the screen size and therefor on mobile devices the user would be scrolling past them for
an unreasonable amount of time before reaching the navigation buttons. That was not a very good user experience. To account for that I used a media query to hide one of the pictures at 600 px and make the second image 100% of the width, that way it will resize itself.
another issue that I came across was implementing the hamburger icon for mobile devices. I could get it to appear when the screen size was at the desired size but the Nav buttons stayed as well and the Hamburger would not open. As I would soon come to find with this project, there was a full stop in the css code that shouldn’t be there that was preventing it from working properly. That was a common theme with bugs in my code.
once I realised the mistake that I was making I was able to easily avoid making it in the future and knew what to look for when I had more issues. The issue that game me the most trouble outside of the hamburger icon was the responsive iFrame for the video. I could get the video to play or have the frame bigger than 100 px. it wold not let me do both. So, I deleted the full div containing the video player and started again 
after consulting LinkedIn Learning for a few tips on how to fix my issue. Another issue I had with both the first iterations of my video player and music player was autoplay. I could not get it turned off. every change/ update/ test I had to do on the tunes page reloaded the Daydream believer song repeatedly. At first, I had the songs playing on a separate page once clicked on but after a little research I managed to get it to stop playing automatically thanks to LinkedIn learning. 
</p>

All the links have been tested thoroughly, I would create a section or feature and the I would Click on each link while I was previewing them. All the links worked taking me to each of the desired destination.
in developer tools I resized the screen to simulate mobile device usage to see if media queries have worked correctly. The songs in the tune’s page all play along with the video, the Iframe also responds to the size of the window its displayed in. 
I have tested all the aspects of the Contact Us Page. There will be an error saying "please fill in this field" if one of the mandatory fields are not filled in as well as point to the field where it has detected the error. 
My site has been tested on multiple browsers and multiple screen sizes. Small, medium and large mobile as well as ipad and laptop sizes with no issues.

<b>Amendments</b>
Mid way through the development of my site I had a conversation with my mentor, and we had both concluded that the layout of my site could be tidied up and the original colour scheme needed to be changed. So, because of this my wireframes look nothing like my finished website now. 
Which, to be honest, is all for the better. I feel that my site is cleaner, streamlined and more professional looking than before. I have noticed that the Spotify Widgets are different colours, That is not a qurk of the code as i once thought but it is a feature of the widget put thre by spotify themselves.
It takes on the properties of the album art that it is displaying. Reference <a target = 'blank'href="https://developer.spotify.com/community/news/2018/07/19/new-updates-to-spotify-play-button/">Spotify</a>

<b>Deployment</b>  
I have my <a target = 'blank'href="https://robertpokane.github.io/bandwebsite/">Website</a> github pages. 

The link will take you directly to it. I pushed my code to github, logged into the gitub site and selected my band website repo and published it in the settings>github pages option.
I had started my project on Cloud 9 but once that had shut, I had moved to gitpod, and finally AWS. 


<b>Credits</b>
Content
The text for the Band bios was all copied from various Wikipedia articles:

<ul>wikipedia https://en.wikipedia.org/wiki/Micky_Dolen
<li>Micky Dolenz: wikipedia https://en.wikipedia.org/wiki/Micky_Dolenz</li>
<li>Peter Tork: wikipedia https://en.wikipedia.org/wiki/Peter_Tork</li>
<li>Michael Nesmith: https://en.wikipedia.org/wiki/Michael_Nesmith</li>
<li>Davey Jones: https://en.wikipedia.org/wiki/Davy_Jones_(musician)</li>

I also got the stories for the Tunes ahoy! section in the tunes page from Wikipedia:
https://www.songfacts.com/facts/the-monkees/last-train-to-clarksville

<li>Last train to Clarksville: https://www.songfacts.com/facts/the-monkees/last-train-to-clarksville</li>
<li>I'm a Believer: https://en.wikipedia.org/wiki/I%27m_a_Believer</li>
<li>Daydream Believer: https://www.songfacts.com/facts/the-monkees/daydream-believerr</li>
<li>Stepping Stone: https://en.wikipedia.org/wiki/(I%27m_Not_Your)_Steppin%27_Stone</li>
</ul>


<b>Media</b>
All photos and music used in this site were obtained from Code Institute for the sole purpose of use in this Milestone project


