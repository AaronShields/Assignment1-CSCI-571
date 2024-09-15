# Assignment 1 - Webpage
By: Aaron Shields


Close fonts that aren't quite what I wanted. 
Menu font / Font in blue rectangle : 
- Used Myfonts.com to identify menu font and found it was closest to 'Renos Rough Light' and 'Zing Sans Rust Light Demo Base'. None of these were free so I used Chatgpt to discover that the cloest font that was free on Google Fonts was 'Alegreya Sans SC Light', which was used in this code


CHAT GPT Citation: 

Query: 
What are the closest google fonts to renos rough light

Answer:
The closest Google Fonts to Renos Rough Light are Aquatico and Zing Sans Rust Light Demo Base, as they both share a similar geometric structure and rough, textured style. These fonts offer a good alternative if you're looking for a similar aesthetic but using free resources like Google Fonts.

To integrate these into your project, you can explore options like Alegreya Sans SC Light, which also brings a modern, geometric flair while maintaining legibility​(
WhatFontIs
)​(
WhatFontIs
).

Let me know if you need help integrating any of these fonts into your design!


Most, if not all code follows: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout

The majority of the code is hard-coded, as you'll see a lot of !important prompts and weird font sizes as well as padding sizes. 

The one place I did not use my own code was trying to replicate the graphs in the rectangles: This code is:

.rectangle {
    position: relative;
    background-color: white;
    background-image: 
        linear-gradient(to right, rgba(200, 200, 200, 0.5) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(200, 200, 200, 0.5) 1px, transparent 1px),
        linear-gradient(45deg, rgba(200, 200, 200, 0.5) 1px, transparent 1px),
        linear-gradient(-45deg, rgba(200, 200, 200, 0.5) 1px, transparent 1px);
    background-size: 15px 15px, 15px 15px, 30px 30px, 30px 30px;
    width: 300px;
    height: 500px;
    box-sizing: border-box;
}

This was sourced from CHATGPT, and is 12 lines which falls below the 50 line limit. 

Finally, I have a text editor that runs prettier which stylistically edits the code to make it more readible. 


