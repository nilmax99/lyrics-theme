# Lyrics Theme - A CSS Snippet for Obsidian

A vibrant and animated CSS snippet for Obsidian designed to add a touch of magic and life to your notes.

The "Lyrics Theme" focuses on subtle, elegant animations and beautiful typography to make writing and reading a more delightful experience. It activates on a per-note basis, giving you full control over when to apply its style.

*A preview of the Lyrics Theme in action.*

## ✨ Features

  * **Animated Elements:** Enjoy subtle "lift" animations on paragraphs and headers, and unique hover effects on almost every element.
  * **Custom Typography:** Uses the clean and readable "Nunito" font for a soft and modern feel.
  * **Vibrant Palette:** A beautiful and consistent color scheme with full, native support for both **light and dark modes**.
  * **Shimmering Blockquotes:** A unique shimmer animation glides across blockquotes when you hover over them.
  * **Animated Highlights:** Highlighted text reveals its background with a stylish "grow" animation.
  * **Custom Lists & Tags:** Unordered lists feature a spinning star (✧), ordered lists have custom-designed counters, and tags are styled as "pills" that fill with color on hover.
  * **Wavy Separators:** Horizontal rules (`---`) are replaced with a beautiful animated wave and a central star.
  * **Elegant Links:** Links have a clean, animated underline, with a special "sine wave" effect for virtual (unresolved) links.

## ⚙️ Installation

1.  Download the `lyrics-theme.css` file from this repository.
2.  Open Obsidian and go to **Settings**.
3.  Navigate to **Appearance** \> **CSS snippets**.
4.  Click the **folder icon** next to the "CSS snippets" heading to open your vault's snippets folder.
5.  Move or copy the `lyrics-theme.css` file into this folder.
6.  Return to Obsidian's `Appearance` settings. You should now see "lyrics-theme" in the list. Enable it by toggling the switch next to its name.

## 🚀 Usage

This snippet is designed to be applied on a **per-note basis**. To activate the theme for a specific note, add the following to the note's **properties (frontmatter)** at the very top of the file:

```yaml
---
cssclasses: lyrics-theme
---
```

All elements within that note will now be styled by the Lyrics Theme. To deactivate it, simply remove the `cssclasses` property from the note.

## 🎨 Customization

You can easily customize the theme's core colors by editing the variables at the top of the `lyrics-theme.css` file.

```css
/* --- 1. Font & Color Palette --- */
.lyrics-theme {
  /* -- Accent Colors -- */
  --lyrics-accent: #5e72e4;
  --lyrics-accent-hover: #475ad0;
  /* ...and so on */
}
```

## 📄 License

This theme is released under the **MIT License**. You are free to use, modify, and distribute it as you see fit.