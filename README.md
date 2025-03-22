# Monster Survivors Website

A responsive, SEO-optimized website for hosting the "Monster Survivors" online game using HTML and Tailwind CSS.

![Monster Survivors Website](https://placeholder-for-screenshot.com/monster-survivors.jpg)

## Overview

This project is a single-page website designed to host and showcase the "Monster Survivors" browser game. The site features a responsive design that works well on both desktop and mobile devices, uses an Apple-inspired design aesthetic, and includes SEO optimization.

## Features

- **Responsive Design**: Adapts seamlessly to all screen sizes
- **Game Integration**: Embedded game iframe with proper attributes
- **Apple-Style UI**: Clean, minimal design inspired by Apple's aesthetic
- **SEO Optimized**: Proper meta tags, headings, and canonical URL
- **Modern CSS**: Built with Tailwind CSS for styling
- **No Dependencies**: Single HTML file with CDN-loaded Tailwind
- **Browser Compatibility**: Works across modern browsers

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Responsive design principles
- SEO best practices

## Website Structure

The website consists of the following sections:

1. **Header**: Navigation menu and site logo
2. **Game Title & Introduction**: H1 heading and brief introduction 
3. **Game Embed**: Responsive iframe containing the game
4. **About Section**: Description of the game and its features
5. **How to Play**: Instructions for game controls
6. **More Games**: Suggestions for similar games (placeholder)
7. **Footer**: Site information, links, and contact details

## Deployment Instructions

### Prerequisites

- A web hosting service where you can upload HTML files
- A registered domain (preferably fungames.wiki as referenced in the code)

### Deployment Steps

1. **Upload the File**: 
   - Simply upload the `index.html` file to your web server's root directory
   - No build process or compilation is required

2. **Domain Configuration**:
   - Point your domain to your web hosting service
   - The canonical URL in the HTML is set to `https://fungames.wiki/monster-survivors`

3. **Testing**:
   - Verify that the game loads correctly in the iframe
   - Test the website on different devices to ensure responsiveness
   - Check that all links work properly

## Customization Guide

### Updating Content

To update the website content, edit the following sections in the HTML file:

- **Game Title & Description**: Update the H1 and paragraph text in the main section
- **About Section**: Modify the game description paragraphs
- **How to Play**: Change instructions to match your game's controls
- **More Games**: Replace placeholder game suggestions with actual games

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

To change the color scheme, modify these color values in the script section.

### Updating the Game

To embed a different game, replace the iframe source URL:

```html
<iframe 
    src="https://cloud.onlinegames.io/games/2025/unity/monster-survivors/index-og.html" 
    class="w-full h-full border-0"
    title="Monster Survivors Game"
    allow="fullscreen; accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    loading="lazy">
</iframe>
```

## SEO Features

The website includes the following SEO elements:

- **Title Tag**: `Monster Survivors - Survive Endless Waves of Monsters | FunGames.wiki`
- **Meta Description**: Optimized description of the game
- **Meta Keywords**: Relevant keywords for the game
- **Canonical URL**: `https://fungames.wiki/monster-survivors`
- **Headings Structure**: Proper H1, H2, and H3 hierarchy
- **Semantic HTML**: Proper use of semantic elements like section, header, footer, etc.

## Browser Compatibility

The website is compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## License

[Specify your license information here]

## Contact

For questions or support:
- Email: contact@fungames.wiki
- Website: [fungames.wiki](https://fungames.wiki)

---

Created with ❤️ for gaming enthusiasts everywhere. 