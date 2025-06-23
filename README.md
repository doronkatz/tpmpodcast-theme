# Episode - Ghost Theme

A modern, podcast-focused Ghost theme designed for content creators and storytellers.

## Description

Episode is a clean and professional Ghost theme specifically designed for podcasters, content creators, and anyone looking to share their stories in an engaging format. The theme focuses on audio content presentation while maintaining excellent readability and user experience.

## Features

- **Podcast-focused design** - Optimized for audio content and episode listings
- **Responsive layout** - Looks great on all devices
- **Customizable typography** - Choose between Wide and Narrow typography styles
- **Flexible navigation** - Multiple layout options (Logo left, center, or stacked)
- **Email subscription integration** - Built-in newsletter signup
- **Podcast platform links** - Direct integration with Apple Podcasts, Spotify, and YouTube Music
- **Custom colors** - Configurable background colors
- **SEO optimized** - Built with Ghost's best practices

## Requirements

- Ghost version 5.0.0 or higher
- Node.js for development

## Installation

1. Download the theme files
2. Upload to your Ghost installation's `content/themes/` directory
3. Restart Ghost
4. Activate the theme in Ghost Admin → Design

## Development

### Prerequisites

- Node.js
- npm or yarn

### Setup

```bash
# Install dependencies
npm install

# Start development with live reload
npm run dev

# Build for production
gulp zip
```

### Available Scripts

- `npm run dev` - Start development server with live reload
- `npm test` - Run theme validation with gscan
- `npm run zip` - Create production-ready theme package

## Customization

The theme includes several customization options available in Ghost Admin → Design → Customize:

### Typography
- **Wide** - Spacious layout with generous margins
- **Narrow** - Compact layout for focused reading

### Navigation Layout
- **Logo on the left** - Traditional header layout
- **Logo in the middle** - Centered branding
- **Stacked** - Vertical navigation layout

### Colors
- **Background Color** - Customize the site's background (default: #ebebeb)

### Homepage Settings
- **Primary Header** - Main headline text
- **Secondary Header** - Subtitle or call-to-action
- **Email Signup Text** - Newsletter subscription message

### Podcast Links
- **Apple Podcasts Link** - Direct link to your show
- **Spotify Link** - Spotify podcast URL
- **YouTube Music Link** - YouTube Music channel

## File Structure

```
episode/
├── assets/          # CSS, JS, and image assets
├── partials/        # Handlebars partial templates
├── default.hbs      # Main template
├── index.hbs        # Homepage template
├── post.hbs         # Individual post template
├── page.hbs         # Static page template
├── author.hbs       # Author page template
├── tag.hbs          # Tag page template
├── home.hbs         # Custom homepage template
├── package.json     # Theme configuration
├── gulpfile.js      # Build configuration
└── LICENSE          # MIT License
```

## Configuration

The theme supports various configuration options through Ghost's settings:

- **Posts per page**: 3 (configurable)
- **Image sizes**: Responsive images with multiple breakpoints
- **Card assets**: Enhanced post card styling

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## License

This theme is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

For support and questions:

- Check the [Ghost documentation](https://ghost.org/docs/)
- Visit the [Ghost forum](https://forum.ghost.org/)
- Review theme documentation at [episode.ghost.io](https://episode.ghost.io/about/)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test with `npm test`
5. Submit a pull request

## Changelog

### Version 1.0.0
- Initial release
- Podcast-focused design
- Customizable typography and layout options
- Social media and podcast platform integration
- Email subscription functionality

---

Created with ❤️ for the Ghost community
