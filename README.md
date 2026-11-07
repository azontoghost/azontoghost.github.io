# Dark Neon Portfolio

A sleek, dark-themed, neon portfolio landing page designed for developers. The page automatically fetches your GitHub profile information and recent public repositories to display them elegantly.

## Features

- **Dynamic Content:** Automatically fetches profile details (name, bio, avatar) and recent public repositories from GitHub.
- **Responsive Design:** Optimized for all screen sizes, from desktops to mobile phones.
- **Dark Neon Theme:** A modern, futuristic look with glowing cyan and purple accents.
- **Single Page Application:** Smooth scrolling navigation for a seamless user experience.
- **Zero Dependencies:** Built with pure HTML, CSS, and JavaScript. No external libraries or build tools required.

## Technologies Used

- **HTML5:** Semantic structure for accessibility and SEO.
- **CSS3:** Custom properties (variables), grid, flexbox, and advanced gradients/shadows for styling.
- **JavaScript (ES6):** Fetch API for GitHub integration and DOM manipulation.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/azontoghost/dark-neon-portfolio.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd dark-neon-portfolio
   ```

3. **Open the file:**
   Since this is a static project, simply open `index.html` in your favorite web browser.
   ```bash
   open index.html
   # or on windows
   start index.html
   # or on linux
   xdg-open index.html
   ```

## Customization

To make this portfolio your own, you'll need to update a few lines in the `index.html` file.

1. Open `index.html` in a text editor.
2. Scroll to the bottom of the file where the `<script>` tag begins.
3. Locate the `username` variable and change it to your GitHub username:
   ```javascript
   const username = 'your-github-username';
   ```
4. You can also customize the colors by editing the CSS variables within the `:root` block at the top of the `<style>` section.
5. Update specific text sections in the HTML (like the "About Me" text or the email addresses in the "Contact" section) as needed.

## License

This project is open-source and available under the MIT License.
