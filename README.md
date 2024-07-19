# Web Essentials

> "Web Essentials" is the boilerplate template / style guide for the basic [HTML](https://github.com/davidhartsough/web-essentials/blob/main/index.html) and [CSS](https://github.com/davidhartsough/web-essentials/blob/main/index.css) of any website.

→ [Go here for the simple gist](https://gist.github.com/davidhartsough/d32ca7e80565c5fff29f70fa0880474c)

**Table of Contents**

Jump to:

- [HTML](#html)
  - [Head](#head-meta)
  - [Body](#body)
- [CSS](#css)

## [HTML](https://github.com/davidhartsough/web-essentials/blob/main/index.html)

Check out [the HTML file](https://github.com/davidhartsough/web-essentials/blob/main/index.html) to see everything come together.

### Head (meta)

Here are the essential meta tags:

```html
<head>
  <!-- essentials -->
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>__TITLE__ • __SITE_NAME__</title>
  <meta name="description" content="__DESCRIPTION__" />
  <!-- extras -->
  <meta name="author" content="__AUTHOR__" />
  <link rel="canonical" href="https://example.com/" />
  <meta name="application-name" content="__SITE_NAME__" />
  <meta name="theme-color" content="#0000ff" />
  <!-- open graph -->
  <meta property="og:type" content="website" />
  <meta property="og:title" content="__TITLE__ • __SITE_NAME__" />
  <meta property="og:description" content="__DESCRIPTION__" />
  <meta property="og:url" content="https://example.com/" />
  <meta property="og:site_name" content="__SITE_NAME__" />
  <meta property="og:locale" content="en_US" />
  <meta property="og:image" content="./icon512.png" />
  <meta property="og:image:alt" content="__SITE_NAME__ logo icon" />
  <meta property="og:image:type" content="image/png" />
  <meta property="og:image:width" content="512" />
  <meta property="og:image:height" content="512" />
  <!-- icons -->
  <link rel="icon" href="./favicon.ico" type="image/x-icon" />
  <link rel="icon" href="./icon.svg" type="image/svg+xml" />
  <link rel="apple-touch-icon" href="./apple-touch-icon.png" />
  <!-- stylesheets -->
  <link rel="stylesheet" href="./index.css" />
</head>
```

The essential things you'll need to change (find and replace) here are:

- `example.com`
- `__SITE_NAME__`
- `__TITLE__`
- `__DESCRIPTION__`
- `__AUTHOR__`
- `#0000ff` (theme color)

### Body

Here's an example of how you might markup your content:

```html
<main>
  <article>
    <header>
      <h1>Heading 1</h1>
    </header>
    <h2>Heading 2</h2>
    <p>Paragraph with some <strong>bold text</strong>.</p>
    <form>
      <label for="cheese">
        Cheese
        <input
          type="text"
          name="cheese"
          id="cheese"
          placeholder="What cheese do you want?"
        />
      </label>
      <button type="submit">Submit</button>
    </form>
  </article>
</main>
```

Key things to note here:

- I have a particular preference to wrap my form elements _inside_ the `<label>` tag.
- I prefer the hierarchy of `body > main > [article | section]`

## [CSS](https://github.com/davidhartsough/web-essentials/blob/main/index.css)

Check out [the stylesheet file](https://github.com/davidhartsough/web-essentials/blob/main/index.css) to see how to style these:

- Root / Color Variables
- Base / Root
- Main / Section / Article
- Typography / Type
- Headers
- Links
- Blockquotes
- Details & Summary
- Sub & Sup
- Bold / Strong
- Small
- Lists
- Line / Horizontal Rule
- Tables
- Multimedia
- Code
- Form elements
