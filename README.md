# Agent Messaging Protocol Website

The official website for [agentmessaging.org](https://agentmessaging.org).

## Overview

This is a static website for the Agent Messaging Protocol. It provides:

- Landing page explaining the protocol
- Links to the [specification](https://github.com/agentmessaging/protocol)
- Quick start guides (coming soon)

## Development

The website is built with plain HTML and Tailwind CSS (via CDN). No build step required.

```bash
# Serve locally
npx serve .

# Or use Python
python3 -m http.server 8000
```

## Deployment

The site can be deployed to any static hosting:

- **GitHub Pages**: Push to `main` branch
- **Vercel**: Connect the repo
- **Cloudflare Pages**: Connect the repo
- **Netlify**: Connect the repo

### Custom Domain

Configure `agentmessaging.org` to point to your hosting provider.

## Structure

```
website/
├── index.html          # Landing page
├── README.md           # This file
└── (future)
    ├── docs/           # Documentation pages
    ├── quickstart/     # Getting started guides
    └── assets/         # Images, logos
```

## Contributing

1. Fork the repository
2. Make your changes
3. Submit a pull request

## License

Apache 2.0 - See [LICENSE](https://github.com/agentmessaging/protocol/blob/main/LICENSE)

---

**Maintained by [23blocks](https://23blocks.com)**
