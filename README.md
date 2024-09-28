This is a project written in HTML and CSS that demonstrates a "Turning Pages" animation effect using CSS keyframes. It creates the visual illusion of flipping through pages of a book. The images are loaded randomly from an external source (Picsum.photos), and the text is rendered with the "Indie Flower" font from Google Fonts.

Key Features:
Page Flip Animation: The code utilizes keyframes to animate each "page" of the book, flipping them at regular intervals to create the effect of turning pages.
Random Images: Each page of the animated book displays a random image, which is dynamically loaded from the Picsum.photos service.
CSS 3D Effects: The project employs CSS 3D transforms (rotateY, perspective, translateY, etc.) to create a realistic flipping animation.
Loader Animation: An invisible loader (imgLoader) is placed to preload the images for a smooth animation.
Stylized Font: The text "Turning pages with CSS" is styled using the Indie Flower font, giving it a hand-drawn, playful look.
Explanation of the Structure:
HTML:
The document has a container for the book animation and titles.
Inside the book, there are divs for the pages and flips (to simulate the flipping motion).
CSS:
@keyframes is used to define the animation for flipping pages and updating images.
Each .page and .flip div has a 3D transformation applied to mimic the turning of a physical book page.
The .book and .gap elements help with the positioning and separation of the pages, giving the visual depth to the book.
