# RasADM Blog

Welcome to the RasADM Blog repository! This is the source code for our technology blog hosted on GitHub Pages.

## 🚀 Live Site

Visit our blog at: [https://rasadm.github.io](https://rasadm.github.io)

## 📝 About

RasADM Blog is your premier destination for technology insights, tutorials, and industry news. We cover everything from web development and programming to emerging technologies like AI, blockchain, and cloud computing.

## 🛠️ Technology Stack

- **Platform**: GitHub Pages
- **Static Site Generator**: Jekyll
- **Theme**: Minima (with custom modifications)
- **Styling**: Sass/SCSS
- **Content**: Markdown
- **Version Control**: Git

## 🏗️ Local Development

To run this blog locally on your machine:

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem
- Git

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/rasadm/rasadm.github.io.git
   cd rasadm.github.io
   ```

2. **Install dependencies**:
   ```bash
   bundle install
   ```

3. **Run the local server**:
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser** to `http://localhost:4000`

### Development Commands

- `bundle exec jekyll serve` - Start local development server
- `bundle exec jekyll serve --drafts` - Include draft posts
- `bundle exec jekyll build` - Build the site for production
- `bundle exec jekyll serve --livereload` - Auto-refresh on changes

## 📁 Project Structure

```
rasadm.github.io/
├── _config.yml          # Site configuration
├── _posts/              # Blog posts
├── _layouts/            # Page templates
├── _includes/           # Reusable components
├── _sass/               # Sass stylesheets
├── assets/              # Images, CSS, JS
├── about.md             # About page
├── contact.md           # Contact page
├── index.md             # Homepage
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## ✍️ Writing Posts

### Creating a New Post

1. Create a new file in the `_posts` directory
2. Use the naming convention: `YYYY-MM-DD-title-of-post.md`
3. Add front matter at the top of the file:

```markdown
---
layout: post
title: "Your Post Title"
date: 2025-01-06 10:00:00 +0000
categories: [category1, category2]
tags: [tag1, tag2, tag3]
author: "Author Name"
---

Your content goes here...
```

### Front Matter Options

- `layout`: Usually `post` for blog posts
- `title`: The title of your post
- `date`: Publication date in YYYY-MM-DD HH:MM:SS +TIMEZONE format
- `categories`: Array of categories
- `tags`: Array of tags for better organization
- `author`: Author name
- `excerpt`: Custom excerpt (optional)

### Writing Tips

- Use clear, descriptive titles
- Include relevant tags and categories
- Add code blocks with syntax highlighting:
  ````markdown
  ```javascript
  console.log("Hello, World!");
  ```
  ````
- Include images in the `assets/images/` directory
- Use internal links: `[Link Text](/about/)`

## 🎨 Customization

### Theme Customization

The blog uses the Minima theme with custom modifications. You can customize:

- **Colors**: Edit variables in `_sass/minima.scss`
- **Layouts**: Override layouts in the `_layouts/` directory
- **Includes**: Add reusable components in `_includes/`
- **CSS**: Add custom styles in `assets/css/style.scss`

### Site Configuration

Main site settings are in `_config.yml`:

- Site title and description
- Author information
- Social media links
- Plugin configuration
- Build settings

## 🔧 Deployment

This site is automatically deployed via GitHub Pages when changes are pushed to the `main` branch.

### Deployment Process

1. Make your changes locally
2. Test using `bundle exec jekyll serve`
3. Commit and push to the `main` branch:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```
4. GitHub Pages will automatically build and deploy your changes

## 🤝 Contributing

We welcome contributions to the blog! Here's how you can help:

### For Writers

1. Fork this repository
2. Create a new branch for your post
3. Write your post following our guidelines
4. Submit a pull request

### For Developers

1. Fork this repository
2. Create a feature branch
3. Make your improvements
4. Test locally
5. Submit a pull request

### Contribution Guidelines

- Follow our writing style and tone
- Ensure all links work correctly
- Test your changes locally before submitting
- Write clear commit messages
- Include relevant tags and categories

## 📊 Analytics & SEO

The site includes:

- Google Analytics (configure in `_config.yml`)
- SEO optimization via `jekyll-seo-tag`
- Sitemap generation via `jekyll-sitemap`
- RSS feed via `jekyll-feed`

## 🐛 Issues & Support

If you encounter any issues or have suggestions:

1. Check existing [GitHub Issues](https://github.com/rasadm/rasadm.github.io/issues)
2. Create a new issue if needed
3. Contact us via our [contact page](/contact/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [GitHub Pages](https://pages.github.com/) - Free hosting
- [Minima Theme](https://github.com/jekyll/minima) - Base theme
- Our amazing contributors and readers

---

**Happy blogging!** 🎉

For more information, visit our [about page](/about/) or [contact us](/contact/). 