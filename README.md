# justanotherday.life

### File Structure Overview

Here's a quick overview of the important folders and files in your blog's directory:

- **content/**: This is where your blog posts and pages live.
- **static/**: Store all your images, videos, and other media files here.
- **themes/**: Contains the themes used to style your blog.
- **hugo.toml**: Configuration file for your Hugo site.
- **archetypes/**: Templates for new content.

### Adding Content

#### Creating a New Post

1. **Navigate to the `content/` Folder:**

   - All your blog posts are stored here.

2. **Create a New Markdown File:**

   - To create a new blog post, simply add a new file with a `.md` extension inside the `content/` directory. Example: `my-new-post.md`.
   - Each file represents a blog post. You can name the file anything you like, as long as it ends with `.md`.

3. **Write Your Content:**
   - Open the new `.md` file with any text editor.
   - Add the following at the top of the file (front matter):
     ```toml
     ---
     title: "My New Post"
     date: 2024-08-09
     draft: false
     ---
     ```
   - Below this, you can start writing your blog post in Markdown format.

#### Organizing Content

- **Sections:**
  - You can organize your content by creating subfolders inside the `content/` directory. For example, if you want a section called "blog," create a `content/blog/` folder and place your posts there.
- **Pages:**
  - For standalone pages (like "About" or "Contact"), create a `.md` file directly in the `content/` directory or in a specific section.

### Adding Images and Media

1. **Place Your Images in the `static/` Folder:**

   - Inside the `static/` folder, create a subfolder (e.g., `images/`) to store your images.
   - Example: `static/images/my-photo.jpg`.

2. **Use the Image in a Post:**

   - To add an image to your post, reference it like this in your Markdown file:
     ```markdown
     ![Alt text](/images/my-photo.jpg)
     ```

3. **Other Media:**
   - You can also add videos, PDFs, or other files in the `static/` folder and link to them in your posts.

### Customizing Your Blog

- **Themes:**
  - Themes are located in the `themes/` directory. To change the theme, open the `hugo.toml` file and update the theme setting.
- **Layouts:**
  - If you need to customize the layout of your posts or pages, check the `layouts/` folder. This is for more advanced users, so you might not need to modify this right away.

### Deploying Your Blog

Once you've added content and customized your blog, you're ready to deploy it. This might involve pushing your changes to a GitHub repository or uploading the files to a web server. For detailed instructions, you might want to check Hugo's official [documentation](https://gohugo.io/documentation/) or reach out to someone who can help with deployment.

### Conclusion

That's it! You now have the basics to start adding content, images, and customize your Hugo blog. If you run into any issues or need further customization, refer to Hugo's documentation or seek help from someone with technical experience.

Happy blogging!
