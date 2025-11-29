# Berkeley EML Documentation

This repository contains the MyST Markdown documentation for the UC Berkeley Econometrics Laboratory (EML).

## Building the Site

This site is built using [MyST](https://mystmd.org/), a powerful markdown-based documentation system.

### Prerequisites

```bash
npm install -g mystmd
```

### Local Development

To build and serve the site locally:

```bash
myst start
```

This will start a local development server and open the site in your browser.

### Building for Production

To build the static site:

```bash
myst build --html
```

The built site will be in the `_build/html` directory.

## Project Structure

- `myst.yml` - Main configuration file
- `*.md` - Content pages
- `motd/` - Message of the Day blog posts
- `images/` - Static images and assets

## Contributing

For questions or issues, contact:
- trouble@econ.berkeley.edu - Technical support
- consult@econ.berkeley.edu - Consulting
