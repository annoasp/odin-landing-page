This is a small repo for the 2nd TOP project, Landing Page.

So far just the example images that we need to replicate in creating our web page, and also this readme which will be more descriptive of the project as things progress.

I'll also add some learnings once complete to see if there were any particular stumbling blocks, new things I've picked up in the process of making the site, and that sort of thing!

Step 1

Added Google's Roboto font using 'font-family' in style.css and a link in index.html's head. Also added Verdana as a web-safe option, and then sans-serif as a fallback. Inspecting the index.html in my browser shows Roboto being selected as intended when I put some example text into the page.

Step 2

Introduced the basic scaffolding for the page in the index.html in preparation for adding the flexboxes and more general styling.

I opted to split the page up into six sections: Header, Hero Section, Info Section, Quote, Call to Action, Footer. Each main section is then broken down into further divs, with appropriate classes in each case, which should allow enough specificity when it comes to styling the page.

I won't be adding any images, just sticking to the most basic design, but there are still containers there that could be used if/when any images were added in the future.

Step 3

I opted to tackle the visual styling of all sections of the page at the same time, since multiple areas shared elements of the same styling. So I've specified the colours and sizing and styling of the text to match what we were given in the example images. I tried to lay the sections out in a logical order so they are easy to return to later, i.e. colour choices, font sizing, font styling, and so on. I'm then left with the work on flexboxes and the more general positioning elements like padding and margin and so on to complete.

It feels like it's going to match up well to the requested design, perhaps one or two extra div containers might be needed to ensure I can achieve the exact positioning asked for.

One thing I did forget to work on were the boxes, buttons and borders.

So some of the obvious todos are: the image placeholder in the hero section needs a grey background. Make sure the call to action button has a solid white border. Add solid blue borders to the image boxes in the info section. Add rounded corners to the buttons, the info boxes, and the main call to action box. Add a max width to the page elements, perhaps 1000px for the main containers in the header, hero section, call to action, and footer. And a slightly reduced 800px for the info section and quote.