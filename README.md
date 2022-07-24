# PORTFOLIO WILLIAM BOLLS

![wireframe](/assets/images/readme-image.png)

## Description of Process
I began by creating a wireframe drawing of where I wanted to place everything on the screen which can be seen above.
I knew that in order to maker everything nice and mobile responsive flex boxes were the way to go, so I made sure to pay special attention to where flex boxeswould need to be stacked on the page.
I placed a bunch of card divs inside a flexbox, and I made each of those cards into a flex box as well that contained a image, and a seperate section where all the text would be placed.
The minicards on the coding projects page are all contained in an aditional flex box that spreads them evenly across the page on their own line.

Once I had the basic layout down I decided to spruce it up a bit with a nice background and borders for the cards. 
I liked the idea of making a website that looked like it was handmade, so I used the border image css property along with border image slice to create borders that scaled with the page easily.
Once I had given the page some of these stylistic flourishes I began working on allowing it to scale properly to mobile devices. This was a bit harder than creating the base page, but I managed it well enough barring a few tricky situations.
one of these was that the flex boxes were not all set to column, which caused some weird issues when the page was scaled down, but once I remembered the flex-direction property it was an easy fix.
The thing that caused me the most issues with scaling however was that for awhile some elements of the page were bigger than the viewport which would cause a phone screen to begin zoomed in with the image off to the side and all elements with a width of auto to be to short.
Eventually I realised this and fixed it by removing the side margins for a variety of objects when the screen became smaller.

Overall I am pretty pleased witht the result, although I would like to possibly change the border image to one that looks a bit nicer.
Additionally, as of right now the navigation buttons on the index will jump to the card with the matching ID, wth the exception of the About Me button, I would rather they link directly to the page.
I made it like this because in the assignment requirements this was listed, but on the other pages they behave more in line with how I want them to.
Also, I want to quickly add that the image of me for the about me section is not the final image that will appear on the page. I just used it as a placeholder because I thoughtt it was funny. Same with the images of monkeys working at computers.
