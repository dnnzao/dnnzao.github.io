# Images for Portfolio Website

This folder is for storing all the images used in your portfolio website.

## How to Add Images

1. **Project Images**: 
   - Save your project images here with descriptive names
   - Recommended: Use optimized JPG or WebP formats (800x600px or similar)
   - Update the `image` property in your backend content.json file to match the filename

2. **Profile Photo**:
   - Save your profile photo as `profile.jpg` or `profile.webp`
   - Recommended: Square format (400x400px)
   - Uncomment the image tag in the Hero.jsx component to display it

3. **Other Images**:
   - Logo images and icons can also be placed here
   - Use clear naming conventions (e.g., logo.svg, icon-python.svg)

## Example Image Setup

For project images, update your backend data:

```json
"projects": [
  {
    "id": 1,
    "title": "Project Name",
    "description": "Project description",
    "technologies": ["Tech1", "Tech2"],
    "github": "https://github.com/yourusername/project",
    "image": "project1.jpg"  // This filename must match your image in this folder
  }
]
```

For your profile photo, uncomment in Hero.jsx:

```jsx
<div className="hero-image">
  <img src="/images/profile.jpg" alt="Dênio Barbosa" />
</div>
``` 