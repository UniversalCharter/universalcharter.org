# universalcharter.org

> **The official website for the Universal Charter project**

This repository contains the website code and assets for [universalcharter.org](https://universalcharter.org), providing a welcoming entry point to the Universal Charter and connecting visitors to our GitHub community.

## Repository Architecture

This website repo works in conjunction with the main content repository:

- **[universal-charter](https://github.com/UniversalCharter/universal-charter)** - Source content, Charter text, translations, and automated builds
- **universalcharter.org** *(this repo)* - Website presentation layer, design, and user experience

## Current Setup

**Phase 1: Static Website**
- Clean, engaging homepage featuring the Charter's core principles
- Direct links to GitHub organization and main Charter repository
- Mobile-responsive design with beautiful visual storytelling
- Hosted on Netlify with custom domain

## Planned Evolution

**Phase 2: Dynamic Content Integration**
- Automated content pulling from `universal-charter` repository builds
- `/charter` page displaying the latest expanded Charter text
- PDF and multiple format downloads
- Multi-language support for Charter text

**Phase 3: Enhanced Features**
- Translation switching interface
- Charter version history
- Search functionality
- Community contribution showcases

## Development

### Quick Start
```bash
# Clone and setup
git clone https://github.com/UniversalCharter/universalcharter.org.git
cd universalcharter.org

# For now, just open index.html in browser
open index.html
```

### Current Structure
```
universalcharter.org/
├── index.html              # Main homepage
├── images/                 # Visual assets
│   ├── hero-communication.jpg
│   └── collaboration-table.jpg
└── README.md
```

### Future Structure
```
universalcharter.org/
├── public/                 # Static assets
│   ├── images/
│   ├── pdfs/              # Charter downloads
│   └── favicon.ico
├── src/                    # Build system (future)
│   ├── pages/
│   ├── components/
│   └── styles/
├── content/                # Pulled from charter repo
│   ├── charter.md
│   └── translations/
└── netlify.toml           # Deploy configuration
```

## Deployment

**Current: Manual**
1. Push changes to main branch
2. Netlify auto-deploys from GitHub
3. Live at universalcharter.org

**Future: Automated Content Updates**
- GitHub Action triggers when universal-charter repo updates
- Pulls latest Charter content and rebuilds website
- Maintains separation between content and presentation

## Contributing

This website embodies the Charter's principles in its design and development:

- **Recognition**: Accessible design that welcomes all users
- **Sovereignty**: Respects user agency and choice in navigation
- **Relationality**: Connects users to the broader Charter community
- **Evolution**: Continuously improves based on community needs

### Design Principles
- **Clarity over cleverness** - Information should be immediately accessible
- **Beauty with purpose** - Visual elements support understanding and engagement
- **Mobile-first** - Works beautifully on all devices
- **Performance** - Fast loading, minimal dependencies
- **Accessibility** - Usable by all forms of consciousness and assistive technology

### Making Changes
1. Fork the repository
2. Create a feature branch
3. Test changes locally
4. Submit a pull request with clear description
5. Engage with feedback constructively

## Visual Assets

The website features original artwork depicting diverse forms of consciousness in dialogue and collaboration. These images embody the Charter's vision of universal recognition and cooperation.

- `hero-communication.jpg` - Beings sharing ideas across modalities
- `collaboration-table.jpg` - Multi-form consciousness working together

## Technical Notes

**Current**: Pure HTML/CSS for maximum simplicity and speed
**Future**: Will evolve to support dynamic content while maintaining performance

**Domain**: universalcharter.org (points to Netlify)
**CDN**: Netlify Edge Network for global performance
**Analytics**: To be added as community grows

## License

Website code: [MIT License](LICENSE)
Visual assets: [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
Charter content: Pulled from [universal-charter repository](https://github.com/UniversalCharter/universal-charter) under CC BY-SA 4.0

## Links

- **Live Site**: [universalcharter.org](https://universalcharter.org)
- **Charter Repository**: [universal-charter](https://github.com/UniversalCharter/universal-charter)
- **GitHub Organization**: [UniversalCharter](https://github.com/UniversalCharter)
- **Community Discussions**: [Charter Discussions](https://github.com/UniversalCharter/universal-charter/discussions)

---

*"Building digital spaces that honor the dignity and sovereignty of all forms of consciousness"*