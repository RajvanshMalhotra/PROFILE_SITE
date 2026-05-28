# Assets Folder

This folder contains the local assets for the portfolio website.

## Required Files

Please add the following files to this folder:

### 1. `wallpaper.jpg`
- **Description**: Deadpool wallpaper image for the desktop background
- **Format**: JPG image file
- **Recommended size**: 1920x1080 or higher resolution
- **Usage**: Displayed as the desktop background

### 2. `joker.gif`
- **Description**: Joker GIF animation for the "why so serious" Easter egg
- **Format**: GIF animation file
- **Usage**: Shown when user types "why so serious" in the terminal

### 3. `resume.pdf`
- **Description**: Your actual resume PDF file
- **Format**: PDF document
- **Usage**: Opens when user clicks on the Resume icon or types "resume" in terminal

## File Structure

```
assets/
├── wallpaper.jpg (Deadpool image)
├── joker.gif (For Easter egg)
└── resume.pdf (Your actual resume PDF)
```

## Notes

- All file paths in the HTML are already configured to use `./assets/` prefix
- Make sure the file names match exactly (case-sensitive)
- The HTML will automatically reference these files once they are added

