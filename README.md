# Web Essentials

## [HTML](https://github.com/davidhartsough/web-essentials/blob/main/index.html)

Check out [the HTML file](https://github.com/davidhartsough/web-essentials/blob/main/index.html) to see everything come together.

### Head (meta)

Here are some of the essential meta tags:

```html
<head>
  <!-- essentials -->
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>__TITLE__</title>
  <meta name="description" content="__DESCRIPTION__" />
  <!-- extras -->
  <meta name="keywords" content="__KEYWORDS__" />
  <meta name="author" content="__AUTHOR__" />
  <link rel="canonical" href="https://example.com/" />
  <meta name="application-name" content="__TITLE__" />
  <meta name="theme-color" content="#000000" />
  <!-- open graph -->
  <meta property="og:type" content="website" />
  <meta property="og:title" content="__TITLE__" />
  <meta property="og:description" content="__DESCRIPTION__" />
  <meta property="og:url" content="https://example.com" />
  <meta property="og:site_name" content="__TITLE__" />
  <meta property="og:locale" content="en_US" />
  <meta property="og:image" content="https://example.com/icon512.png" />
  <meta property="og:image:alt" content="__TITLE__ logo" />
  <meta property="og:image:type" content="image/png" />
  <meta property="og:image:width" content="512" />
  <meta property="og:image:height" content="512" />
  <!-- twitter -->
  <meta name="twitter:card" content="summary" />
  <meta name="twitter:title" content="__TITLE__" />
  <meta name="twitter:description" content="__DESCRIPTION__" />
  <meta name="twitter:site" content="@__TWITTER_SITE__" />
  <meta name="twitter:creator" content="@__TWITTER_CREATOR__" />
  <meta name="twitter:image" content="https://example.com/icon512.png" />
  <meta name="twitter:image:alt" content="Correla logo icon" />
  <meta name="twitter:image:type" content="image/png" />
  <meta name="twitter:image:width" content="512" />
  <meta name="twitter:image:height" content="512" />
  <!-- icons -->
  <link rel="icon" href="/favicon.ico" type="image/x-icon" sizes="any" />
  <link rel="icon" href="/icon16.png" type="image/png" sizes="16x16" />
  <link rel="icon" href="/icon32.png" type="image/png" sizes="32x32" />
  <link rel="icon" href="/icon192.png" type="image/png" sizes="192x192" />
  <link
    rel="apple-touch-icon"
    href="/apple-icon.png"
    type="image/png"
    sizes="180x180"
  />
  <!-- stylesheets -->
  <link rel="stylesheet" href="index.css" />
</head>
```

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
