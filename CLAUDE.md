# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands
- `bundle exec jekyll serve` - Run the site locally with live reload
- `bundle exec jekyll build` - Build the static site
- `docker-compose up` - Run the site in a Docker container

## Validation/Test Commands
- `bundle exec htmlproofer ./_site` - Validate HTML in built site

## Project Structure
- _includes/: HTML components used across the site
- _layouts/: Page templates 
- _sass/: SCSS style files
- assets/: Static assets including JS, images, and main SCSS file
- images/: Image files for the site

## Code Style Guidelines
- HTML: Use semantic elements, maintain proper indentation
- SCSS: Follow BEM naming convention when possible
- Liquid: Keep logic in templates minimal, use includes for components
- YAML: Use consistent indentation (2 spaces)
- Ruby: Follow standard Ruby conventions

## Version Control
- Keep commit messages clear and descriptive
- Test all changes locally before committing
- Ensure the site builds successfully after changes

## Content Updates
- Maintain consistent formatting in Markdown content
- Use proper heading hierarchy (H1 → H2 → H3)
- Optimize images before adding to repository