# Making Research Software FAIR with CodeMeta

Mini-site for the **RSECon26 workshop** “Making Research Software FAIR with CodeMeta”.

The site is intentionally built with plain HTML and CSS so that it can be published directly with **GitHub Pages** and edited easily by workshop organisers.

## Repository structure

```text
.
├── index.html
├── style.css
├── README.md
├── exercises/
│   ├── generate-codemeta.md
│   └── mapping-exercise.md
└── resources/
    ├── mapping-template.csv
    └── llm-mapping-prompt.md
```

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Copy all files from this folder into the repository.
3. Commit and push the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`.
7. Save.

GitHub will publish the site at a URL similar to:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Content to update before the conference

The proposal did not include final public details for:

- workshop date
- room/location
- final organiser list
- repository URL
- shared communication channel
- slides
- final fallback schema for Exercise 2

These can be added to `index.html` once confirmed.

## Workshop structure

The 180-minute workshop combines short presentations, demonstrations and two hands-on activities:

1. Generate and improve CodeMeta metadata.
2. Map another metadata schema into CodeMeta.

## Accessibility

The site uses responsive layouts, semantic HTML, high contrast, large headings and no JavaScript dependency.
