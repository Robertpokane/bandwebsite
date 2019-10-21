<h1> The Monkees  </h1>


<b>One or two paragraphs providing an overview of your project</b>.

In this, the first milestone project, I will implamenting what I have learned and what I can do at this early stage of my coding career. 
For this project I had loads of ideas:
<ul>
<li>A live news feed for the <b>Index</b> page </li>
<li>Links to the bands Spotify/youtube/twitter/facebook on every footer</li> 
<li>Album playlists that changed the song list when clicked on on the shopping page</li> 
<li>Monthly news letter subscription</li>
<li>different payment options</li>
<li>audio sampling of songs</li>
<li>online shop with constantly updating merchendise</li>
<li>Automatic update on home page if a new item has added</li>
<li>notice apearing on the top of the home page that all first time orders have an instant 33% discount</li>
<li>Monkees TV show episodes/ clips fromt he show</li>
</ul>

<p>After carefull consideration I have decided on a number of features to include for the opening versions of my project and what can be implimented for the future versions.</p>

<p>For the initial version of my project I have implimented a news setion in the Index page, right now it is filled with Lorem text as to give the band an idea as to what it is going to look like.
from the limited library that I have to hand. I was able to get a few of the songs and almbum covers implimented into the tunes section. Each of the songs has an exerpt from wikipeda beside it to 
give the user a glimse into the history of the piece, beside what we have, as the main attraction the music video of Daydream Believer.

<b>UX</b>

<p> My UX process is a pretty simple one. I start with my end goal and work backwords taking each step as a stepping stone to reach how I shoulld start my project as explaine above. 
My aim was to provide an avenue for fans of the band, long term and new fans, to find out somethibng they didnt previously know about the band. Weither that is through our news feature or through the stories in tunes we always have something to offer.


My focus for the site is to keep the user's attention engaged. this is done in a number of ways. First of all we need a eye catching story to put on the front page, music to stimulate the mind while they read an amusing anecdote abut the piece that they are listening to. where we can then direct them to our shop where sonds, digital and physical can be sold, limited edition merchandise, signed posters
what ever the band wants to sell. We can collect email addresses and Send out a monthly email with Stories, a "this day in History" freature (example on this day 12th June 1967 was the first ever episode of the monkees or Micky Dolenz birthday.) new items available from the shop. Thing like that. </p>

What I aim to achieve:

<b>Jimmy:</b>


"as sombody that was born long after the rise of the monkees, I wanted to get to know what the bad was like what sort of music they making, what the tv show was like, so I naturally gravitated towards the site, 
It has all the information i need, as well as a music, music videos, stories from behind thesceens and more!"

<b>Tommy:</b>


"I grew up listening to the monkees on the radio and watching them on the tv. I have followed there career from the first comedic musical beginings in 1966 until today. The website keeps me updates with everything that is going on today."

<b>Julie:</b>

"I am an avid collecter of music and music memberoilia. I have Such a soft spot for all things Monkee releated. The news letter keeps me up-to-date with sales happening in the store and when there is anything new I can add to my collection "

These are the 3 core user types that I bases my site around, from my <a href="assets/Wireframes/Band website mockup.bmpr">wireframes</a> as a strating point to the stories on the stories on the <a href="tunes.html">Tunes</a> page to the music and Merchandise that will be available on the <a href="shop.html">Shop</a> page

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:


In addition,my plans for the future of this website is to:

<ul>

<li>Have either clips or full episode on the monkees tv show</li>
<li>Have a customisable merchendise page, names, </li>
<li>Run monthly competitions to recieve signed merchandise</li>
<li>Set up a Monthly News letter called "Monkee Around Monthly"</li>

</ul>


Technologies Used

Once I took stock of all the technoliges used for my project I was genuinly surprise at the ever growing list that I amased. 

<ul>

<li>HTML 5 fot the basic lay out and structuer of the site</li>
<li>CSS for the colour and style of the site </li>
<li>Google fonts for the style of the writing in the site <a target = 'blank'href="https://fonts.googleapis.com/css?family=Chicle"> Google Fonts</a></li>
<li>Font Awesome fot the small styliesd icons (facebook, twitter, spotify icons) <a target = 'blank'href="https://fontawesome.com">Font Awesome</a></li>
<li>Hover for the hover effects when navigating <a target = 'blank'href="https://cdnjs.com/libraries/hover.css">CDNJS</a></li>
<li>Bootstrap for the navigation button style <a target = 'blank'href="https://getbootstrap.com/https://getbootstrap.com/">Bootstrap</a></li>
<li>Jquerry as Bootstrap relays on it <a target = 'blank'href="https://jquery.com">Jquery</a></li>
<li>I used alot of the information on the Code Instatute course allong with all of the music and pictures of the band <a target = 'blank'href="https://codeinstitute.net/">Code Institute</a></li>
<li>LinkedIn learning fort the responsive Iframe for the music video <a target = 'blank' href="https://www.linkedin.com/learning/">LinkedIn Learning</a></li>
<li>All of the information I used regarding the Bios and stories surronding the music was taken from <a target = 'blank'href="https://en.wikipedia.org/wiki/Main_Page">Wikipedia</a></li>
<li>EmailJS to send and recieve emails via the contact page <a target = 'blank'href="https://www.emailjs.com/">EmailJS</a></li>
</u>

<h2>Testing</h2>

<p>My approch to testing was a break it as you go type of approch. I would make a feature and test what I would need to do un render the site unuseable. so for example on index.html. I had alot of issues with the navigaition buttons and the images at the top of the page. The images remained the same size no matter the screen size and therefor on mobile devices the user would be scrolling pas them fOR
an unreasionable amount of time before reaching the navigation buttons. That was not a very good user experience. To account for that I used a media querry to hide one of the pictures at 600 px and make the second image 100% of the width, that way it will resize itself.
another issue that I came accross was implamenting the hamburger icon for mobile devices. I could get it to appear when the screen size was at the desired size but the Nav buttons stayed aswell and the Hamburger would not open. As I would soon come to find with this project, there was a full stop in the css code that shouldnt be there that was preventiing it from working properly. That was a common theme with bugs in my code.
once I realised the mistake that I was making I was able to fairly easily avoid making it in the future and knew what to look for when I had more issues. The issue that game me the most trouble outside of the hamburger icon was the responsive iFrame for the video. I could get the video to play or have the frame bigger than 100 px. it wold nto let me do both. So I deleted the full div containging the video player and started again 
after consulting linkedin Learning for a few tips on how to fix my issue.  </p>

All of the links have been tested thourghly, I would create a section or feature and the I would Click on each link while I was previewing them. All of the links worked taking me to each of the desired destination.
in developer tools I reszed teh screeen to simulate mobile device usage to ses if media querries have worked correctly. The songs in the tunes page all play along with the video, the Iframe also resonds to the the size of the window its displayed in. 
I have tested all of the aspects of the Contact Us Page. There will be an error saying "please fill in this field" if one of the mandditory fields are not filled in as well as point to the field where it has detected the error. 
My site has been tested on multible browsers and multible screen sizes. Small, medium and large mobile aswell as ipad and laptop sizes with no issues.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for the Band bio's was all copied from various Wikipedia articles:

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


Media
All photos and music used in this site were obtained from Code Institute frot eh sole purpose of use in this Milestone project

# interactive-front-end-developement-project
