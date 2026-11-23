# Profile Card Block

A simple WordPress block that allows users to display a person's picture, name, title, and short biography in a profile card.

**Author:** Phillip Slade  
**Course:** COSW 240  
**Project Type:** WordPress Block

## Overview

The goal of this project is to create a simple profile card that can be added to a WordPress page or post. It could be used to introduce an author, employee, or team member.

## Features

- Add a profile picture.
- Enter a person's name.
- Enter their title or position.
- Add a short biography.
- Display everything together in one card.

## How It Will Work: For the User

The user will add the Profile Card block to a WordPress page or post. They will be able to select a picture and enter the person's information. The block will display that information in a simple card.

## How It Will Work: Behind the Scenes

The block will use basic WordPress block editor tools to let users enter information and select an image.

I plan to use:

- `block.json` to describe the block.
- `index.js` to handle the block's editing and display.
- `RichText` for the text fields.
- `MediaUpload` to select a profile picture.
- `style.css` to control the card's appearance.
- A PHP file to register the block with WordPress.

## Planned File Structure

```text
cosw240-profile-card/
├── README.md
├── cosw240-profile-card.php
├── block.json
├── index.js
├── index.asset.php
└── style.css
```

## Project Milestones

- [x] Choose a project idea.
- [x] Create a GitHub repository.
- [ ] Research the basic WordPress block documentation.
- [ ] Set up the basic block files.
- [ ] Add the picture and text fields.
- [ ] Style the profile card.
- [ ] Test the block in WordPress.

## Questions and Challenges

- How do I add an image from the WordPress Media Library?
- How do I make the information appear correctly in the profile card?
- How do I style the card so it looks clean and organized?

## Resources

- [WordPress Block Editor Handbook](https://developer.wordpress.org/block-editor/)
- [WordPress Block Metadata](https://developer.wordpress.org/block-editor/reference-guides/block-api/block-metadata/)
- [WordPress RichText Documentation](https://developer.wordpress.org/block-editor/reference-guides/richtext/)
