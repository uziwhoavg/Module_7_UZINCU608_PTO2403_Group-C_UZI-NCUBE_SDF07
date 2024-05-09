# [SDF07] Project: CodeSpace Pets Instagram Profile

REFERENCES : 
https://codepen.io/GeorgePark/pen/VXrwOP
https://codepen.io/SitePoint/pen/wKdrwN
https://www.instagram.com/uzi.trizzle/
https://www.kunkalabs.com/tutorials/mixitup-grid-layouts/*/

Essentially,
I implemented various styles for a mock instagram profile and gallery layout, including font styles, layout adjustments for responsiveness, and hover effects for gallery items. in summary:

Base Styles had already been set
- with a Set  base font size to 10px. reference for rem purposes?
- Applied box-sizing border-box globally.
Defined a font family called "Roboto" and specified its variants for regular text and numbers.

Body Styles:
Set the body font family to "Roboto".
Set background color to white and text color to black.
Adjusted padding and line-height.

Profile Styles:
Styled profile sections such as image, user settings, user name, edit button, statistics, and biography.
Used flexbox for layout and alignment.
Applied specific font sizes, weights, and line heights for different elements within the profile section.

Gallery Styles:
Styled the gallery layout using CSS grid for responsiveness.
Applied hover and focus effects for gallery items.
Set specific font sizes, weights, and alignment for gallery item info.
Positioned the gallery item type ( in the top right corner of each gallery item.

Media Queries:
Adjusted styles for smaller screens using @media queries, particularly targeting screen widths up to 900px.
Modified layout, font sizes, and padding for better responsiveness on smaller devices.

Overall, i created a somewhat responsive and visually appealing layout for a profile and gallery section using CSS.


HTML Structure:
A typical HTML structure was given with <head> and <body> sections.
Meta tags for character set and viewport settings were included.

External CSS file above was linked, including the custom stylesheet (styles.css) and Font Awesome for icons.

Header Section:
The header contains the profile information, including the profile image, username, edit profile button, and settings button.
Profile statistics such as the number of posts, followers, and following are displayed.
A brief bio is included describing the purpose of the profile and a dedication to my first ever dog who passed away.

Main Content Section:
The main content section contains the gallery of pet images.
Each image is displayed within a gallery item container, including image tags and information about likes and comments.
Icons from Font Awesome are used for likes, comments, and video indicators.
The gallery items are laid out in a grid format.

Loader:
A loader element is included, presumably for indicating simulating loading progress given that one reaches the pages end .