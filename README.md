# TRANSPOSE Website

Static website for the TRANSPOSE organization and TDToolkit ecosystem.


## File Structure

```
transpose-org.github.io/
├── index.html              # Home page
├── tdtoolkit.html         # TDToolkit components hub
├── data.html              # Data resources and access tiers (not added yet)
├── governance.html        # Governance structure (not added yet)
├── community.html         # Community resources (not added yet)
├── contribute.html        # Contributing guidelines (not added yet)
├── publications.html      # Publications and citations (not added yet)
├── roadmap.html          # Development roadmap (not added yet)
├── contact.html          # Contact information (not added yet)
├── code-of-conduct.html  # Code of conduct (not added yet)
├── assets/
│   ├── css/
│   │   └── style.css     # All styles (< 200 lines)
│   └── og.png            # Social media preview image (placeholder)
└── README.md             # This file
```

## Editing Content

### TDToolkit Components

To edit the TDToolkit component cards in `tdtoolkit.html`:

1. Find the card div for the component you want to edit
2. Update the title, description, and links
3. Categories are styled with CSS classes: `tag-data`, `tag-benchmark`, `tag-method`

To add a new component:

```html
<div class="card">
    <div class="card-header">
        <h3>Component Name</h3>
        <span class="tag tag-[category]">Category</span>
    </div>
    <p>Component description goes here.</p>
    <div class="card-actions">
        <a href="https://github.com/transpose-org/[repo]" target="_blank" rel="noopener" class="btn-link">Repository →</a>
        <a href="#" class="btn-link">Docs →</a>
    </div>
</div>
```

### Navigation

The navigation menu is duplicated across all pages. To add or modify navigation items:

1. Update the nav menu in all HTML files
2. Keep the order consistent
3. Mark the current page with class `active`

### Styling

All styles are in `assets/css/style.css`. The design uses:
- CSS custom properties for theming
- System font stack for performance
- Mobile-first responsive design
- Utility classes for spacing and layout

## Maintenance

### Regular Updates

- Update publication list as papers are published
- Refresh roadmap quarterly
- Update maintainer list when roles change
- Add new components to TDToolkit page
- Update year in footer annually

### Creating the Social Image

Replace the placeholder `assets/og.png` with an actual image:
1. Create a 1200x630px image
2. Include TRANSPOSE branding
3. Add the tagline
4. Save as PNG with optimization


## License

MIT License - See repository for details

## Contact

For questions about the website: guirado@berkeley.edu
