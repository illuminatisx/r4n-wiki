# Wiki Images

This directory contains all images used in the Rust4Noobs wiki.

## Directory Structure

- `/wiki/image/monuments/` - Images for monument guides
- `/wiki/image/survival/` - Images for survival guides
- Add more directories as needed for new categories

## How to Add Images

1. **File Format**: Prefer JPG for photos and screenshots, PNG for diagrams and images with transparency
2. **File Size**: Keep images under 1MB when possible to ensure fast loading times
3. **Resolution**: Images should be at least 1200px wide for good detail, but don't need to be larger than 1920px
4. **Naming Convention**: Use descriptive names with hyphens, like `launch-site-overview.jpg`

## How to Reference Images in Wiki Articles

In your Markdown files, reference images like this:

```markdown
![Descriptive Alt Text](/wiki/image/category-name/image-name.jpg)
```

For example:

```markdown
![Launch Site Overview](/wiki/image/monuments/launch-site-overview.jpg)
```

## Image Optimization

Please optimize your images before uploading:
- Compress JPGs to reduce file size
- Remove metadata when possible
- Consider using WebP format for better compression 