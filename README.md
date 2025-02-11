# The Wayfinder's Log - Personal Blog

This is the repository for my personal blog, "The Wayfinder's Log", built using the [Hugo theme Stack](https://github.com/CaiJimmy/hugo-theme-stack). The blog shares perspectives and insights from my journey across continents and careers - from Papua New Guinea to Montana, from air traffic control to web development.

## About the Blog
"The Wayfinder's Log" explores the intersection of technology, literature, family, and faith. It's a space where I share:
- Technical insights from web development and homelab experiences
- Reflections on literature, philosophy, and the classics
- Stories from my air traffic control career
- Thoughts on family life and coaching
- Adventures in coffee brewing and calligraphy

## Technical Details
This blog is built with:
- Hugo static site generator
- Hugo Theme Stack
- Deployed to VPS

## Local Development
To run this site locally, you'll need:
1. Git
2. Go
3. Hugo Extended version

Clone the repository and run:
```bash
hugo server
```

## Theme Updates
To update the theme manually:
```bash
hugo mod get -u github.com/CaiJimmy/hugo-theme-stack/v3
hugo mod tidy
```

## Deployment
```bash
hugo --minify
rsync -avz /path/to/source username@destination_server:/path/to/destination
```

## Configuration
- Main configuration files are in the `config` folder
- Content is organized in the `content` folder
- Site parameters can be adjusted in `config/_default/params.toml`

## Contact
For any questions or suggestions about the blog, feel free to reach out through [logan@fireflysoftware.dev](logan@fireflysoftware.dev).