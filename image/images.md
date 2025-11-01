The code automatically converts relative paths like image/image.jpg to the full GitHub raw URL: https://raw.githubusercontent.com/gavined1/blog-content/main/image/image.jpg
Examples you can now use in your frontmatter:
imageUrl: "image/image.jpg" → auto-converts to full GitHub URL
imageUrl: "image/photos/my-photo.png" → auto-converts to full GitHub URL
imageUrl: "https://external-site.com/image.jpg" → uses as-is (external URLs still work)
