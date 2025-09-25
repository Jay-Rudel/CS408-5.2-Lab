# CS408 - M5.2 Lab
    Holding

## Getting Started
    To get started, clone this repository, and then you can learn 
    to view it in the "Viewing" section. Which is below.

    There are tests for this project so you will need to run the following command: 
    
    ```npm install```

## Viewing
    I highly recommend using VSCode Live Server extention to see the project. This allows you to
    see the page, and interact with the page without having to open it in a local file.

    The file that you will be looking at for this project in my github is called "index.html"

## Verification
    TODO: Holding

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers

    Color:
        The current colors: black text with Green background. Fails every single one of the contract checker from the following Site:https://webaim.org/resources/contrastchecker/

        In order to fix we change the green to a more contracting color with black making it closer to white. This fixes all of the issues that were found as well.

    Semantic HTML
        1. When trying to navigate using the keyboard almost everything works besides the comment section. Which I fixed by changing from a div to a button.
        2. I changed the Font tags to h1, h2, and h3 depending on the size of the tag. If size = 6, became a h2. 
        3. I changed the div element in <div class="nav"> to a <nav> element also fixing the CSS to represent that.

    The Images
        Alt text has been added to both images. This is made up but it is described to the best of my ability.

    The Audio Player:
        1. As deaf people were unable to hear the audio, I added a translation too it. I was unable to get a button to work so I just added it as a paragraph.
        2. Order browsers that dont allow for the audio, I added a download for them if the audio doesnt load.

    The Forms

    The Show/Hide Comment Control

    The Table
        We add a summary of the table inside of a <caption> tag under the initial <table> tag.

    Other Considerations?
        1. I think one of the big things is the read ability of the normal <p> size. To me it feels small in some points
        2. Overall, some of the padding from element to elment seems a bit extreme. I feel like it would be better suited not to be so large.

## References / If needed
    The only source I used for this project was the
    reading that was provided to us. Just to make sure
    I could figure out how to do the nav bar. As that was
    what I had problems coding.