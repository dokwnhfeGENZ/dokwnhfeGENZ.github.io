---
layout: post
title: "Getting Started with GitHub Pages: Host Your Blog for Free"
date: 2026-09-16
categories: github tutorial
---

# Getting Started with GitHub Pages: Host Your Blog for Free

If you're a developer, you probably already use GitHub. But did you know you can host a free blog directly from a GitHub repository? In this guide, I'll walk you through setting up your own GitHub Pages blog in minutes.

## Why GitHub Pages?

**GitHub Pages is perfect for developers because:**

- 🚀 **Completely free** - No hosting costs
- 🔗 **Native GitHub integration** - Your audience already knows GitHub
- 📝 **Version control built-in** - Track every change to your blog
- ⚡ **Fast and reliable** - Powered by GitHub's infrastructure
- 🎨 **Customizable** - Use Jekyll, Hugo, or plain HTML/CSS
- 🔐 **Secure** - HTTPS by default

## What You'll Need

- A GitHub account (you probably have this!)
- Basic knowledge of Git and Markdown
- About 10 minutes of your time

## Step 1: Create the Repository

1. Go to [github.com/new](https://github.com/new)
2. Name your repository: **`yourusername.github.io`**
   - Replace `yourusername` with your actual GitHub username
   - **This is important!** The name must follow this exact pattern
3. Make it **Public** (required for Pages)
4. Check "Add a README file"
5. Click **Create repository**

## Step 2: Add Jekyll Configuration

Jekyll is a static site generator that GitHub Pages uses automatically. Add a `_config.yml` file to your repo:

```yaml
title: My Awesome Blog
description: A blog about coding and development
author: Your Name
theme: minima

# Site settings
url: "https://yourusername.github.io"
baseurl: ""

# Social links
github_username: yourusername
```

## Step 3: Create Your First Post

Posts go in a `_posts` folder with the filename format: `YYYY-MM-DD-post-title.md`

**Example: `_posts/2026-09-16-hello-world.md`**

```markdown
---
layout: post
title: "Hello World!"
date: 2026-09-16
categories: blogging
---

# My First Post

This is my first blog post. I'm excited to share my thoughts on [topic here].

## What I'll Be Writing About

- Development tutorials
- Open source insights
- Coding tips and tricks

Stay tuned! 🚀
```

## Step 4: Enable GitHub Pages

1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under "Build and deployment"
   - Source: **Deploy from a branch**
   - Branch: **main** (or master)
   - Folder: **/ (root)**
4. Click **Save**

GitHub will build your site in a few minutes. You'll see a green checkmark when it's done.

## Step 5: Visit Your Blog!

Your blog is now live at: **`https://yourusername.github.io`**

## Tips for Success

### 📚 Writing Consistently
- Aim for one post per week
- Write about things you're learning
- Share your projects and experience

### 🎯 Topics That Resonate with Developers
- How-to tutorials
- Project post-mortems
- Lessons learned
- Open source contributions
- Tool reviews and comparisons
- Debugging stories

### 🔗 Promote Your Posts
- Add link to your GitHub bio
- Share in relevant communities
- Link to posts in your PRs and issues
- Tweet about new posts

### 🎨 Customize Your Blog
- Change themes in `_config.yml` (try: `minima`, `slate`, `cayman`)
- Create an `about.md` page
- Add a `contact.md` page
- Create a `_layouts/` folder for custom designs

## Common Gotchas

**❌ Posts not showing up?**
- Check the filename format: `YYYY-MM-DD-title.md`
- Check the YAML front matter (the `---` section at the top)

**❌ Site not building?**
- Check your `_config.yml` for syntax errors
- Look at the Actions tab to see build logs

**❌ URL not working?**
- Wait 5 minutes for the initial build
- Check that your repo name is exactly `yourusername.github.io`

## Next Steps

1. ✅ Create your repo
2. ✅ Add config file
3. ✅ Write your first post
4. ✅ Enable GitHub Pages
5. 📝 Start blogging!

---

## Further Reading

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Documentation](https://jekyllrb.com/)
- [Markdown Guide](https://www.markdownguide.org/)

Happy blogging! Feel free to reach out on GitHub if you have questions. 🚀
