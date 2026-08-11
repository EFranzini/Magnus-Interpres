# Magnus Interpres

Magnus Interpres is a small, self-contained web app for working with pairs of text.
Like I've written in the repo description: "Just a simple and straight forward interface to help on book translations, because nowadays software are full of useless stuff."

The interface is intentionally styled like a classic Windows 95 application. It provides two text boxes per pair, allowing you to place related text side by side—for example, an original text on the left and a translated or processed version on the right.

## Features

- **Side-by-side text pairs** — each pair has a left and right text area.
- **Add pairs** — create as many additional text pairs as needed.
- **Remove pairs** — delete pairs when they are no longer needed.
- **Reset** — click the reset button three times quickly to return to a single empty pair.
- **Export** — download all right-side text as a `.txt` file, with a blank line between entries.
- **No dependencies** — everything is contained in a single HTML file.
- **Classic UI** — the application uses a Windows 95-inspired visual style.

## How to use

1. Open `magnus_interpres.html` in a web browser.
2. Enter your text into the left and right boxes.
3. Use the **➕** button to add another pair.
4. Use the **✖** button on a pair to remove it.
5. Use the **🛫** button to export all right-side text to `magnus_interpres_export.txt`.
6. To reset the workspace, click the **♻️** button three times within 1.5 seconds.

## Project structure

This project is intentionally simple:

```text
.
└── magnus_interpres.html
```

The HTML file contains the complete application, including:

- HTML structure
- CSS styling
- JavaScript behavior

No build step, package manager, server, or external library is required.

## License

No license is currently specified for this project, do whatever you want, idc.
