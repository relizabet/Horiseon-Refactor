# Horiseon-Refactor

## User Story

    AS A marketing agency
    I WANT a codebase that follows accessibility standards
    SO THAT our own site is optimized for search engines

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

## Notes

- Replaced non-semantic div's with semantic elements wherever possible to improve accessibility
-
- Added qualifiers to all css class selectors for more specificity
- Added an alt attribute to each image
- Added empty alt attribute for accessibility to logos in the aside
- Verified all headers used in sequential order
- Made the Company name the title
