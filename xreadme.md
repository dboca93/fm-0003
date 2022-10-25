## Created by Dilhan Boca 
## [Twitter](https://mobile.twitter.com/dboca93)
## Gmail: dboca93@gmail.com
## [Linkedin](https://www.linkedin.com/in/dilhan-boca-a3892294/)
## [Github](https://github.com/dboca93?tab=repositories)

- [Overview](#overview)

With this project, I tried something different by using flex-box within a grid structure. 
The grid structure was simple, one column with three rows. Each grid-box had a flex-box
inside; allowing me to style each one individually. 

Are there any simpler approaches ? Would love your feedback :)

## Completion: 

1. Add the other attribution from the previous document. 
2. Push the completed task. 
3. Then, collect the live/repo links, and come back to the read-me and add these. 
4. Make sure we send a link of these online, and also contact as many people 
online as we can to get some much needed feedback. 

## Links

- Solution URL: [Repo Link](https://your-solution-url.com)
- Live Site URL: [Vercel Link](https://your-live-site-url.com)

## Screenshot

![](images/Screenshot%202022-10-25%20at%2015-36-54%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)

## Resources Used & Lessons Learned

Please make some handwritten notes about these in the future, to
help the muscle memory come into affect. 

1. [dcode](https://www.youtube.com/watch?v=exb2ab72Xhs)

This resource was key to learning how to do the image overlay. 
First, make the image-container relative and then make the overlay
absolute -- with a top:0 and left:0.

It's key to use the opacity: 0 on the initial overlay, and then to have opacity: 1 {and the 
background-color on the hover state aswell}

2. Center image---on another absolute image ---using position absolute. 

    `position: absolute;
    top: 50%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);`

3. Using Variables:

    `--dark-blue-line: hsl(215, 32%, 27%);
    --white: whitesmoke;
    --ff: 'Outfit', sans-serif;`


4. [W3Schools](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_link_mailto)

This was surprisingly easy, clicking on this icon now means that a viewer can 
send me an email directly from their mail app on their computer -- would be interested 
to see if this works on the mobile phone the same way. 

    `<a href="mailto:dboca93@gmail.com" aria-label="email"><i class="lni lni-envelope"></i></a>`
