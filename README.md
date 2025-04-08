# The Adewunmi Lineage

This project is an interactive family tree visualization for "The Adewunmi Lineage," built with HTML, CSS, and JavaScript. It displays the lineage starting with Usman Adewunmi, with a fixed header "The Adewunmi Lineage" at the top, and allows users to explore generations through clickable 3D rectangles.

## Live Demo
View the family tree live at: [https://username.github.io](https://username.github.io)  
*(Replace "username" with your actual GitHub username.)*

## Features
- **Fixed Header**: "The Adewunmi Lineage" remains at the top of the page.
- **Interactive Navigation**: Click a person’s rectangle to view their children, and use the "Back" button to return to previous generations.
- **3D Design**: Rectangles have a 3D effect with shadows and hover animations.
- **Centered Text**: Names are centered within rectangles, even when wrapped.
- **Side-by-Side Children**: All children of a parent appear in a single row, with horizontal scrolling for large generations.
- **Slow Fade Animations**: Children fade in and out over 1 second for a smooth transition.
- **Responsive Layout**: Adapts to different screen sizes, with scrolling for wide rows.

## Structure
- **Root**: "The Adewunmi Lineage" (fixed header, teal: #69b3a2).
- **Generation 1**: Usman Adewunmi (dark blue: #1b263b).
- **Generation 2**: His children (light blue: #57a0ce).
- **Generation 3**: Their children, including Ali’s four wives (orange: #ffa500).
- **Generation 4**: Deepest level, e.g., children of the wives (pink: #ff7575).

## File
- **`index.html`**: The single file containing HTML, CSS (in `<style>`), and JavaScript (in `<script>`). This is all you need to run the project.

## How to Use
1. **Online**: Visit https://edayor.github.io/Family-tree-adewumi/ in your browser.
2. **Locally**:
   - Clone or download this repository:
     ```bash
     git clone https://edayor.github.io/Family-tree-adewumi/
     ```
   - Open `index.html` in a web browser.
3. **Navigation**:
   - Click a rectangle to see its children.
   - Click the "Back" button (top-right) to return to the previous level.
   - Scroll horizontally if a generation has many children.

## Customization
- **Names**: Edit the `familyTree` object in the `<script>` section of `index.html` to change names or add more generations.
- **Colors**: Modify the background colors in the CSS (e.g., `.gen1`, `.gen2`) to adjust the palette.
- **Size**: Adjust `.person` width/height or `font-size` in the CSS for different rectangle sizes.
- **Fade Speed**: Change `transition: opacity 1s ease` to alter the fade duration.

## Deployment
This project is hosted on GitHub Pages:
1. Push `index.html` to the root of your `username.github.io` repository.
2. GitHub Pages automatically serves it at `https://username.github.io`.

## Credits
- Built with assistance from Grok, created by xAI.
- Inspired by the Adewunmi family lineage.

## License
This project is open-source and available under the [MIT License](LICENSE). Feel free to fork and modify it!

---

*Last updated: April 08, 2025*
