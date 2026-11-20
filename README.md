# Daniels · Developer Portfolio

A single-page portfolio design with an introduction, services, categorised project gallery and contact form. Bootstrap provides the navigation and tab behaviour.

[Open the live demo](https://oniseg.github.io/danial/) · [View screenshot](https://raw.githubusercontent.com/onisEg/resume/23df91e50f87b60e1360d79edcc24cf77eb09b07/public/projects/danial.webp)

## Exploring the gallery

1. The navbar links to sections in the same document. On smaller screens the Bootstrap collapse control reveals the available links.
2. The Portfolio section has All, Brand, Design and Graphic pills. Each pill selects its corresponding HTML tab pane; the browser switches between pre-authored groups.
3. The contact section demonstrates name, email and message inputs. The page loads local jQuery, Popper and Bootstrap scripts in sequence for its interactive components.

## Run locally

From the repository root, serve the checked-in files with Python 3:

```sh
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000/) to load `index.html`. The browser reads the HTML, styles and assets directly. On Windows, `py -m http.server 8000` starts the same server.

## Source guide

| File or directory | What to look for |
| --- | --- |
| [index.html](index.html) | Navigation, gallery tab IDs, matching panes and contact markup. |
| [css/style.css](css/style.css) | Portfolio-specific layout and styling. |
| [js](js) | Local JavaScript dependencies for Bootstrap interactions. |
| [images](images) | Photography and project thumbnails. |

## Manual walkthrough

Select each gallery pill and confirm its target pane appears. When adding a new category, give the control and pane matching target IDs. At mobile width also check that the section menu opens and its links scroll to the expected section.

## Project screenshots

![image](https://user-images.githubusercontent.com/35266228/207604077-54e86bb4-7a16-45cd-9fac-fae20a7e8162.png)
