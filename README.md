# Base HTML Project

## Description

This project contains a basic, simple and valid HTML file that demonstrates the fundamental structure of an HTML5 document.

## Files

- `base_index.html` - Main HTML file containing basic HTML5 structure

## Structure

The HTML file includes:

- DOCTYPE declaration
- HTML element with language attribute
- Head section with title and meta charset
- Empty body section

## Technologies Used

- HTML5

## How to View

1. Open `base_index.html` in any web browser
2. The page will display with the title "My First HTML Page"

## Validation

This HTML file is W3C compliant and validates successfully with the official HTML Validator.

## Requirements Met

- Uses only HTML (no external libraries)
- W3C compliant code
- All files end with a new line
- README.md file included at project root



index.html README
# HTML Project README

## Project Overview

This project involves creating a basic HTML webpage with structured content and interactive elements. You'll be working with fundamental HTML components to build a functional web page.

## Getting Started

### Step 1: File Setup
Copy your existing `base_index.html` file to `index.html`. This will serve as your main webpage file.

```bash
cp base_index.html index.html
```

### Step 2: Required Content Structure

Add the following elements within the `<body>` section of your `index.html` file:

#### Text Content
- **At least 4 paragraphs** of content using `<p>` tags
- Ensure paragraphs contain meaningful text related to your webpage's purpose

#### Heading Structure
Include a proper heading hierarchy:
- **Level 1 heading** using `<h1>` tag (main page title)
- **Level 2 heading** using `<h2>` tag (section titles)
- **Level 3 heading** using `<h3>` tag (subsection titles)

#### Interactive Image
Add a clickable image with the following specifications:
- Use an image of your choice (suggested: `https://i.ibb.co/gTDZZT8/ALX-Logo-07.png`)
- Make the image clickable by wrapping it in an anchor tag `<a>`
- Link it to any URL of your choice
- Ensure the image displays properly and the link functions correctly

## Example Structure

Your HTML body should follow this general structure:

```html
<body>
    <h1>Main Page Title</h1>
    
    <p>First paragraph content...</p>
    <p>Second paragraph content...</p>
    
    <h2>Section Title</h2>
    <p>Third paragraph content...</p>
    
    <h3>Subsection Title</h3>
    <p>Fourth paragraph content...</p>
    
    <a href="your-chosen-url">
        <img src="https://i.ibb.co/gTDZZT8/ALX-Logo-07.png" alt="Description">
    </a>
</body>
```

## Validation Checklist

Before submitting, ensure your webpage includes:
- [ ] Copied `base_index.html` to `index.html`
- [ ] At least 4 paragraphs in the body
- [ ] One `<h1>` heading
- [ ] One `<h2>` heading  
- [ ] One `<h3>` heading
- [ ] A clickable image that links to an external URL
- [ ] Proper HTML structure and syntax

## Additional Notes

- Use semantic HTML elements where appropriate
- Ensure all images have descriptive `alt` attributes for accessibility
- Test your links to confirm they work correctly
- Consider adding basic styling later to enhance the visual presentation

## Resources

- [HTML Elements Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Headings Guide](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
- [HTML Images and Links](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)
