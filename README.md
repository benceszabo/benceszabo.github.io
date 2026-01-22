# Bence Szabó - Personal Academic Website

This is the source code for my personal academic website, hosted on GitHub Pages.

**Live site:** [https://benceszabo.github.io](https://benceszabo.github.io)

## Built With

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [AcademicPages](https://github.com/academicpages/academicpages.github.io) - Jekyll theme (fork of Minimal Mistakes)

## Local Development

1. Install Ruby and Bundler
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Open `http://localhost:4000` in your browser

## Structure

```
├── _config.yml          # Site configuration
├── _data/
│   └── navigation.yml   # Navigation menu
├── _pages/
│   ├── home.md          # Homepage
│   ├── projects.md      # Research projects
│   ├── teaching.md      # Teaching experience
│   └── cv.md            # Curriculum Vitae
├── images/
│   └── profile.jpg      # Profile photo
└── files/               # PDFs and downloadable files
```

## Updating Content

- Edit markdown files in `_pages/` to update content
- Add PDFs to `files/` directory
- Update `_config.yml` for site-wide settings
- Modify `_data/navigation.yml` for menu items

## Notes

- Remember to add your profile photo as `images/profile.jpg`
- Add your CV PDF as `files/cv.pdf`
- Add paper PDFs to `files/` and update links in `projects.md`
