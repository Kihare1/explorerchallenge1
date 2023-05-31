# Challenge 1 - Explorer
First challenge of a web programming course 

In this challenge I had to fix the bugs on a broken code to make the website look like the original one. So I'll list here what I had to do:
html:
- The function <img> was outside of the first div with the name hero, so I put it up there
- The word "únicos" on the title had the no color, so I made a <span> and colored it up
- On the paragraph the words "exclusivos e únicos" had the color orange, but they were supposed to be bold without any color, so I removed the <span> and switched to <strong> but not including the "e" because it's supposed to not have anything on it
- Following the same logic "dedicação no seu projeto" was bold and was supposed to be orange, so I switched <strong> to <span>
- Also on the Figma project, both "paragraphs" were included on the same paragraph for coding, so I moved that second text which was outside of div: hero and wrote it right after the first text with 2 <br> in between
- On the second text there were some words with orange/bold that weren't supposed to have that so I also switched it up to what they were supposed to be
- The line on the footer was on the first div, so I put it back on the div footer
css:
- text-aling on body was: end so I switched it for center
- the margin on #hero only had a number that was supposed to be bottom, so I fixed it
- the img was getting both images, so I wrote #hero img to fix it and switched the margin from 100px to 72px which was the correct number on Figma
- the margin-botton that represents distance between the title and the text was on h1 span, so I put it on the correct place
- on #balls it showed top: 0 and right: 0, so I switched to bottom: 0 and right: 0, because that's where it's supposed to be
