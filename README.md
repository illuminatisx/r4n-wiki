# Rust4Noobs Wiki Contribution Guide

Welcome to the Rust4Noobs Wiki! This repository contains all the content for our community-driven knowledge base. We appreciate your interest in contributing to make this resource better for everyone.

## How to Contribute

### Getting Started

1. **Fork the Repository**
   - Click the "Fork" button at the top right of [our repository](https://github.com/illuminatisx/r4n-wiki)
   - This creates your own copy of the wiki that you can edit

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/r4n-wiki.git
   cd r4n-wiki
   ```

3. **Create a Branch**
   ```bash
   git checkout -b your-feature-branch
   ```

4. **Make Your Changes**
   - Edit existing files or create new ones following our guidelines below
   - Commit your changes with clear, descriptive commit messages

5. **Push to Your Fork**
   ```bash
   git push origin your-feature-branch
   ```

6. **Submit a Pull Request**
   - Go to your fork on GitHub and click "New Pull Request"
   - Select your feature branch and provide a clear description of your changes

## Wiki Structure

The wiki is organized into categories, each containing multiple articles:

```
/wiki/ (Not part of this repository, but needed for image references!)
├── monuments/
│   ├── launch-site.md
│   ├── military-tunnels.md
│   └── ... other monument guides
├── survival/
│   ├── first-30-minutes.md
│   └── ... other survival guides
└── image/
    ├── monuments/
    ├── survival/
    └── ... images organized by category
```

## Creating New Articles

### File Format

All wiki articles are written in Markdown with YAML frontmatter. Here's a template:

```markdown
---
title: Article Title
description: Brief description of what this article covers
author: YourGitHubUsername
authorLink: https://github.com/yourusername
dateCreated: YYYY-MM-DD
dateUpdated: YYYY-MM-DD
---

## Overview

Start with a brief introduction about the topic.

![Optional Image](/wiki/image/category-name/image-name.jpg)

## Main Section

Your content here...

## Another Section

More content...
```

### Article Guidelines

1. **Use Proper Headings**
   - Main title is already set in the frontmatter
   - Use H2 (`##`) for main sections
   - Use H3 (`###`) for subsections

2. **Keep Content Concise and Informative**
   - Focus on practical information players can use
   - Use bullet points and numbered lists for clarity
   - Keep paragraphs short and focused

3. **Include Relevant Images**
   - Add screenshots or diagrams that help explain concepts
   - Place them in the appropriate `/image/` subdirectory
   - Reference them using proper Markdown syntax (see below)

## Adding Images

1. Place images in the appropriate category folder in `/wiki/image/`
2. Reference them in your Markdown like this:
   ```markdown
   ![Descriptive Alt Text](/wiki/image/category-name/image-name.jpg)
   ```
3. See the [image README](/wiki/image/README.md) for detailed guidelines on image formats and optimization

## Creating New Categories

If you want to create a new category:

1. Create a new folder in the root directory with a lowercase, hyphenated name
2. Create at least one article in the new category
3. Create a corresponding image folder in `/image/`

## Code of Conduct

- Be respectful of other contributors
- Focus on factual information rather than personal opinions
- Avoid content that could be considered offensive or inappropriate
- Give credit where it's due by linking to sources when applicable

## Need Help?

If you have questions about contributing:

- Join our [Discord server](https://discord.gg/r4n)
- Open an issue on the GitHub repository

Thank you for helping make the Rust4Noobs Wiki a valuable resource for the community! 
