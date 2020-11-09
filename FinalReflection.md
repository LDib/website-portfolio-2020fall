Okay! I had a lot of fun doing this one, I always get lost when coding, and the way that my brain works I am way more motivated to do something when I think it's actually going to matter, so since this is going to be my actual band website for the forseeable future, I put in some solid thinking and work. 

I think that I met every baseline criteria for this project. I think the arrangement, size, and color all fit together to guide the viewer quite nicely. Here's a final screenshot of the website:

...

I layed it out so that the margins just have a background image, and the site is more condensed around the center of the page, I created a top banner, menu, and other boxes in ways that I think viewers would be familiar with from other websites, and I used Paletton to create what I think is a pleasing color scheme, even though I'm not an expert on that. Each link leads to another page (the ones to bandcamp and spotify aren't supposed to link to my profiles there yet, that's not a mistake), and you can navigate back to the home page from each internal link from either the "home" menu button or just clicking the "Nicolo" header. There's one sitewide CSS sheet that makes for a uniform header as well as other things like page width and link layout, and then more specific selectors within that sheet for different pages. I use a legally useable image, with attribution (even though it wasn't necessary) and the alt text that background images need. What I mean by this is that background images don't have a specific alt-text attribute like an img, but I searched for and followed the accessibility guidelines for adding alt text to background images. You can see what I did in this code screenshot:

...

My website also displays in a local browser correctly. That preceding sentence and the paragraph before it are my explanation of how I met the baseline criteria.

I also met at least one aspirational criteria from each section we defined, and I think that should qualify me for meeting the aspirational criteria for this project.

For *Media Files,* I created playable media: the "Blues and Greens" mp3, which I learned how to embed, did so, and centered it. Browsers will display that with their default mp3 settings and it should play the song (it works for me and my playtesters). For *Dynamism,* I spent some time making sure that my website is at least reasonably responsive using @media queries. There are three breakpoints for my website, which are when it's on a desktop, tablet or small window on a desktop, and mobile phone. On desktop, it looks as it does in the above screenshot. With a smaller window, the background image becomes obscured and the boxes switch to relative units and resize with the screen, and on mobile the boxes at the bottom stack on top of each other, rather than side by side. Here are some screenshots of that activity: 

...

Additionally in *Dynamism,* I made use of psuedo-classes to style my links in a more yummy way than the default when hovered over, clicked on, and visited. 

For *Coding,* I used Flexbox to lay out my page, and I think that my CSS stylesheet was pretty condensed, and commented well to show where it was doing what. I also think I used selectors well to get at what I wanted to style (like using parent selectors instead of just making another class).

For *Audience Engagement,* I think I used good practices for accessible design in that I separated form from presentation well, and, for example, used h1 as a more important header than h2. My site also loads publicly over the internet at https://ldib.github.io/website-portfolio-2020fall/ ! Also, due to my sitewide stylesheet, I think it has a consistent theme. 

I also appreciated and used the feedback I was given:

...

I mainly used their feedback as confirmation that the page looked okay and made sense, but that the links and structure wasn't exactly clear. I re-styled the links and added "Home" to the menu so that there was no risk of a dead end.

As far as *Reflection* goes, I think having at least one aspirational criteria from each category is very good, and I did use a lot of meaningful commit messages like "Responsive Design!" with a description of what I did under it. I also think that I may have made it seem in class like I've had a lot of experience doing this stuff before because I asked some questions, but this is the second website I've ever made, and the first one was way, way less advanced and a long time ago. I've never used flexbox to this extent, never used responsive design, never had a CSS sheet with even half this many rules, or learned how to make a background image or anything like that. There are many ways I could level this site up, still, but I think I put in a lot of work and have a very good base to work off of. Thanks!

