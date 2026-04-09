# GitHub Pages Workflows

This directory contains workflows for deploying the OpenIPC MkDocs Wiki to GitHub Pages.

## Workflows

- `pages.yml` - Main deployment workflow (recommended)
- `deploy.yml` - Alternative deployment workflow

Both workflows will:
1. Build the MkDocs site
2. Deploy to GitHub Pages
3. Trigger automatically on pushes to main branch

## Requirements

- GitHub Pages must be enabled in repository settings
- Source must be set to "GitHub Actions"
