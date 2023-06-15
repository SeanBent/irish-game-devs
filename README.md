<h1>Irish Game Devs </h1>

<h2>Introduction</h2>
Irish Game Devs is a website that showcases video games created by individuals or game studios in Ireland. It aims to celebrate the talent present in Ireland as well as the creations they have made. This website has also been created in the hopes of encourging new people to become game devs by providing pointers to the organisations and resources available to support them, as well as eduational opportunities in game dev. A means of getting one's own game featured n the site is also present through the contact form.

<h3>The target audiences are:</h3>
-Video game enthusiasts of Ireland and the rest of the world who are interested in Irish-made games and game development in Ireland.


-Indie, mid, and large video game developers in Ireland.


-People interested in becoming game developers in Ireland.


By answering questions such as “What video games have been made in Ireland?”, “What level of quality can be found in games produced in Ireland?" and "How do I become a developer in Ireland?" it is hoped that the site will encourage greater participation in the Irish video game development landscape.

<hr>

<h2>Features:</h2>


1. <h3>Site-wide:</h3>


   Navigation bar that includes links to the Home page, For Developers page, and Contact Us page:
   
   ![navbar](docs/navbar.png)


   
   -Footer containing social media links:

   ![footer](docs/footer.png)
   

2. <h3>The 'Home' page:</h3>
   -A hero image demonstrating a person doing active game development:

   ![hero](docs/hero.png)


   -An explanation of what the site as and what it intends to achieve.
   
   -A section of text that highlights that the site contains resources available to help people to become game developers, and a link to the 'For Developers' page:

   ![explain](docs/explain.png)


   -A featured game of the month section including a youtube video and description of the game, as well as links to websites for the game and the studio:
   
   ![featuredgame](docs/featuredgame.png)

   
   -A 'Recent Releases' section showing recently released Irish games, youtube videos of the games, as well as links to websites for the games and the studios:


   ![recentreleases](docs/recentreleases.png)

   
   -A 'Get your game featured' section pointing users to the Contact Us page where they can fill in a form:


   ![getyoursfeatured](docs/getyoursfeatured.png)
   
   
   
3. <h3>'For Developers' page:</h3>


   -Images relating to Imirt and Pulse college, text explaining Imirt and Pulse College and their use to prospective developers, and links to Imirt and Pulse College Websites.


   ![imirt](docs/imirt.png)


   ![pulsecollege](docs/pulsecollege.png)

   
   
4. <h3>'Contact Us' page:</h3>


   -Form to fill in that can be used by developers to contact the website to get their game featured
   
   -Text explaning the form.
   
   -A background image.

   ![contactform](docs/contactform.png)


5. <h3>'Thank You' page:</h3>
   
   -A page that appears when a user has subitted the form, thanking them for interacting with the site.

   ![thankyou](docs/thankyou.png)
   
<hr>

<h2>Features Left to Implement:</h2>

1. Fully responsive navbar. 
   
2. Fully responsive hero image at higher screen widths
   
3. Styled Submit button on form
   
4. A more comprehensive list of games
   
5. A search bar to search for content by studio, title, and release year.

6.  Profile pages for developers.

<hr>

<h2>Testing</h2>
After some initial code and structure was laid out, the approach for development became a 'mobile first' approach. As content was added and tests conducted, 280px screen width was the starting break point, with subsequent breakpoints being 380px, 440px, 560px, 760px. As screen width increased, many problems began to present themselves and had to be troublshooted. Of particular issue was the fact that many of the stylings were defined in absolute values. This led to overflows and compression of text, as well as sections being stuck on the left of the screen.

Later, the majority of the containers and stylings were swapped over to flex values, allowing more robust placement and elimination of overflows after much testing to find the correct values.

![flexdemo](docs/flexdemo.png)


<h3>Feature Testing</h3>

-Navbar links tests involved clicking on each navbar link in turn on each page, to verify that they correctly redirect the user to the specified page.

-To verify videos displayed and played without loss of aspect ratio or areas being cutoff from viewing involved observing the embedded video, then clicking play on each. Then clicking the fullscreen button to verify the video will display fullscreen.

-To verify the form validation worked, each field would be filled out in turn and then 'Submit' would be clicked. If any field was left blank, the validation message should appear.

![verifyform](docs/verifyform.png)


<h3>Responsivity Testing</h3>

To test responsivity, devtools would be opened and the screen size adjusted either by selecting a specific device's dimensions, or by dragging the sides to adjust the width or height. Then observations were made about the effect the change had on each part of the page. Then css wwould be adjusted to achieve the necessary changes to achieve responsivity.

![ipadtest](docs/ipadtest.png)


![responsive](docs/responsive.png)


<h3>Validator Testing</h2>

HTML: No errors were returned when passing through the official W3C validator.

![index-validation](docs/index-validation.png)

![for-developers-validation](docs/for-developers-validation.png)

![contactus-validation](docs/contactus-validation.png)

![thankyou-validation](docs/thankyou-validation.png)


CSS: No errors were found when passing through the official (Jigsaw) validator.

![css-validation](docs/css-validation.png)

<hr>

<h2>Unfixed Bugs</h2>

1. Navbar responsivity: while in general the site scales better at lower screen sizes, the navbar suffers a very noticable distortion of shape at lower screen widths. At first this was judged an issue that would be addressed later in the project as it was otherwise fully functional, and as more content was added and needed fixing, this feature kept getting put off. Then, with little time remaining the focus needed to turn to larger structural issues and completing the README.
   
   
   ![navbar-bug](docs/navbar-bug.png)
   
   
2. Hero Image: at lower to mid size screens the hero image on index.html scales well. But on higher screen sizes it is overwhelmingly large and breaks the natural flow of the page. With more time to fix this, a likely solution would be to display a cropped image instead at higher breakpoints.


![hero-bug](docs/hero-bug.png)

   
3. Entire area above the navbar is clickable and leads to home page. This is likely due to the block element of the logo extending the entire width of the page.


<hr>


<h2>Deployment</h2>


<hr>


<h2>Credits</h2>


<h3>Content</h3>


<h3>Media</h3>
