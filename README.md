# phlox-landing

## Description

For our course assignment we were tasked to create a hi-fi prototype of a website that enables users to calculate their carbon footprint. The assignment scope consist of the homepage and online registration form only. 

## Requirement / Scope

- Use brand colour (#d600fc)
- Design should be suitable for a 1920x1080 screen
- A single Call to Action to enable users to sign-up
- Meet accessibilty guidelines
- Use Gestalt principles and other Design principles where appropriate
- Implement with vanilla Javascript

## Gestalt Principles 
### Law of Similarity 

- Elements sharing the brand colour. Creates a sense of togetherness; users are part of the brand's family
- Font per navigation and main section. The navigation bar sets a more professional tone, while the main section is more playful and compliments the outer-space theme

### Law of Proximity

- Grouping of navigation links. Indicates the links have a similar function i.e. helps to redirect users to a different part of the site

### Law of Common Fate

- Registration form contains indented fields in each section of the form. Implies a shared relationship between those fields

## Design Principles

- Match between system and the real world: Familiar terminology were referenced in the design
- User control and freedom: A close button was made available on the registration form
- Consistency and standards: Design for important elements follow the convention of most sites. E.g. Sign Up or Log In on the top-right of the site
- Error prevention: Using the appropriate `type` attributes for fields in the registration form
- Aesthetic and minimalist design: Reduced cognitive load by keeping textual information to a mininum on the home page. Used complementary colours

## What I learned

- I was able to provide a better layout between the `img` and `.left-box` by making the following additions to `.container`:
    - Make `img` the child element 
    - Assign `display: flex` and `justify-content: space-around` to the selector

## Future Improvements
- Implement responsive design (This was not a requirement)
- Make better use of space
