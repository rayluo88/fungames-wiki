# FunGames.wiki Website

A responsive, SEO-optimized website for hosting online browser games using HTML and Tailwind CSS.

![Monster Survivors Website](https://placeholder-for-screenshot.com/monster-survivors.jpg)

## Overview

This project is a gaming website designed to host and showcase various browser games, starting with "Monster Survivors". The site features a responsive design that works well on both desktop and mobile devices, uses an Apple-inspired design aesthetic, and includes SEO optimization.

## Features

- **Responsive Design**: Adapts seamlessly to all screen sizes
- **Game Integration**: Embedded game iframes with proper attributes
- **Apple-Style UI**: Clean, minimal design inspired by Apple's aesthetic
- **SEO Optimized**: Proper meta tags, headings, and canonical URLs
- **Modern CSS**: Built with Tailwind CSS for styling
- **No Dependencies**: HTML files with CDN-loaded Tailwind
- **Browser Compatibility**: Works across modern browsers
- **Analytics**: Google Analytics integration for visitor tracking
- **Game Template**: Standardized template for adding new games

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Google Analytics
- Responsive design principles
- SEO best practices

## Project Structure

The repository consists of the following key files:

1. **index.html**: Main homepage featuring the Monster Survivors game
2. **game-template.html**: Template for creating new game pages
3. **README.md**: Project documentation (this file)

## Website Sections

Each game page follows a consistent structure:

1. **Header**: Navigation menu and site logo
2. **Game Title & Introduction**: H1 heading and brief introduction 
3. **Game Embed**: Responsive iframe containing the game
4. **About Section**: Description of the game and its features
5. **How to Play**: Instructions for game controls
6. **Related Games**: Suggestions for similar games
7. **Footer**: Site information, links, and contact details

## Recent Updates

- **Google Analytics Integration**: Added tracking code to monitor site traffic
- **Plants vs Zombies Link**: Updated the "More Games" section with a link to Plants vs Zombies
- **Game Template**: Created a standardized template for adding new games
- **GitHub Repository**: Set up at [github.com/rayluo88/fungames-wiki](https://github.com/rayluo88/fungames-wiki)

## Deployment Instructions

### Prerequisites

- A web hosting service where you can upload HTML files
- A registered domain (fungames.wiki as referenced in the code)
- Git for version control

### Deployment Steps

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/rayluo88/fungames-wiki.git
   cd fungames-wiki
   ```

2. **Upload Files**: 
   - Upload the HTML files to your web server's root directory
   - No build process or compilation is required

3. **Domain Configuration**:
   - Point your domain to your web hosting service
   - Ensure the canonical URLs in the HTML match your domain structure

4. **Testing**:
   - Verify that games load correctly in the iframes
   - Test the website on different devices to ensure responsiveness
   - Check that all links work properly

## Using the Game Template

To add a new game to the website:

1. **Copy the Template**:
   - Duplicate `game-template.html` and rename it for your specific game (e.g., `plants-vs-zombies.html`)

2. **Replace Placeholders**:
   - Replace all uppercase placeholders (GAME_TITLE, GAME_IFRAME_URL, etc.) with your game's specific information
   - Add game-specific descriptions, controls, and tips
   - Update related games section with appropriate links

3. **Add Navigation**:
   - Update the main page to include a link to your new game page

## Google Analytics Integration

The website includes Google Analytics tracking:

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-31TE5NEYTF"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-31TE5NEYTF');
</script>
```

This allows you to track:
- Visitor demographics
- Traffic sources
- User behavior
- Page performance
- Conversion metrics

## Customization Guide

### Updating Content

To update the website content, edit the HTML files:

- **Main Page**: Edit `index.html` to update the homepage
- **Game Pages**: Create new pages from `game-template.html` for each game
- **Navigation**: Update navigation links in all files when adding new pages

### Modifying the Design

The website uses Tailwind CSS with a custom Apple-inspired color palette:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                apple: {
                    light: '#f5f5f7',
                    dark: '#333336',
                    blue: '#0071e3',
                    gray: '#86868b',
                    darkgray: '#1d1d1f'
                }
            }
        }
    }
}
```

To change the color scheme, modify these color values in the script section of each HTML file.

## SEO Features

The website includes the following SEO elements:

- **Title Tags**: Optimized for each game page
- **Meta Descriptions**: Custom descriptions for each game
- **Meta Keywords**: Relevant keywords for each game
- **Canonical URLs**: Properly structured URLs
- **Headings Structure**: Proper H1, H2, and H3 hierarchy
- **Semantic HTML**: Proper use of semantic elements

## Browser Compatibility

The website is compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Contributing

To contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

[Specify your license information here]

## Contact

For questions or support:
- Email: contact@fungames.wiki
- Website: [fungames.wiki](https://fungames.wiki)
- GitHub: [github.com/rayluo88/fungames-wiki](https://github.com/rayluo88/fungames-wiki)

---

Created with ❤️ for gaming enthusiasts everywhere. 