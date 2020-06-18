# Horiseon-Refactor

## User Story

> AS A marketing agency
> I WANT a codebase that follows accessibility standards
> SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards  
WHEN I view the source code  
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements  
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements  
THEN I find accessible alt attributes

WHEN I view the heading attributes  
THEN they fall in sequential order

WHEN I view the title element  
THEN I find a concise, descriptive title

## To Do

[] create alt text for all images
[x] correct website name
[x] make links change color on hover
[x] create nav tag for navigation bar
[] resolve id's not being in css?
[] make horiseon title an img?
[x] correct path for nav css elements
[x] changed background image to <img> tag and removed from css for accessibility

## Notes

- no id's being used in css, but there are id's in the html
- site is not set up to be 'scalable'
- probably need to use flex-box here
- color being declared multiple times, can i do this all at the beginning?
- replace px with em's
- make nav accessible by keyboard
