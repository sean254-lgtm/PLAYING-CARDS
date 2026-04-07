# PLAYING-CARDS

Overview
This is a simple HTML and CSS project that displays playing cards with different suits and values.

File Structure
HTML (index.html)
The HTML file creates a layout for displaying playing cards with the following structure:

Main Container (#playing-cards): A flex container that holds all the cards
Card Elements (.card): Individual card divs containing:
Left section (.left): Displays the card value and suit in the top-left corner
Middle section (.middle): Displays the suit symbol(s) centered on the card
Right section (.right): Displays the suit symbol and value in the bottom-right corner (rotated text effect)
Cards Included:
Ace of Spades (A ♠)
Two of Clubs (2 ♣) - with two suit symbols
Three of Diamonds (3 ♦) - with three suit symbols
CSS (styles.css)
Styling for the card layout:

Body
Background Color: Purple (#bd34eb)
Playing Cards Container
Display: Flex layout with centered items
Gap: 20px spacing between cards
Wrap: Cards wrap to next line on smaller screens
Card Styling
Width/Height: 200px × 200px
Background: Light purple (#eae1ed)
Padding: 10px
Border: 1px solid black with 10px border-radius
Shadow: Box shadow effect (0 0 10px #000)
Layout: Uses flexbox with space-between to position elements
Section Positioning
Left: Positioned at top-left (flex-start)
Middle: Centered vertically (center)
Right: Positioned at bottom-right (flex-end)
Typography
Font Weight: Bold
Font Size: 1.2rem
Color: Red (.one, .two classes) for red suits (Clubs and Diamonds)
Features
Responsive flexbox layout
Clean, card-like design with shadows and rounded corners
Suit symbols displayed in appropriate positions (corners and center)
Color-coded red and black suits
