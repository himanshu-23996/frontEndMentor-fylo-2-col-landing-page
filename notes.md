 # Be careful on

- Semantic Tags
  - Two H2s followed by a paragraph, and an h3 in footer
- Use Clamped Font
- Use Responsive Sizing on logo and the images used
- Use form tag for email box
- Use auto or fr on grid units
-All fonts are opensans except the header top bar, main section heading and the footer title



# Components of page:

- Body :
- Use pancake layout for body
  - 04. Pancake Stack --> 1 line layout


- Header: Make another container inside it, margined from all sides
  - Top Bar : flexed, space between justified
    - Logo
    - Links on right:use (flex:30%) or something like that for its width
      - For them use flex, space-evenly justified and centrally aligned
  - For the title section
      - Mobile: rowed, image on top (column reversed) followed by text pane
      - Desktop:
        - Right-image dynamically sized
        - Left Pane: Title,para,Email form
- Main
  - Two sections
    - For Section 1:
       -  Mobile: rowed, image on top (column reversed) followed by text pane
       -  Desktop:
        - Right-image dynamically sized
        - Left Pane: Title,link,testimonial
    - For Section 2
      - Desktop : Grided
        - Left : h3, para
        - Right : Email form
      - Mobile:
        - Left on top, followed by form 
- Footer
  - Mobile : Simple Grid layout column based
  - Desktop Grid based



# Problems
- Header top bar sizing in mobile mode --> Fixed
- Header hero section buttong sizing in mobile mode --> Fixed
- Display Profile in Testimonial sub-section in main section 1  --> Fixed
- Main top curved bg --> Background Color in the main sec-1 overlaps the top bg
- Footer social icons bordering issue and border color change on hovering
- 