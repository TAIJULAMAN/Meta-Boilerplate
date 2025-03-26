# 🌐 HTML Meta Tags Boilerplate

This README includes a collapsible HTML boilerplate snippet with common meta tags, followed by detailed explanations for each tag.

---

<details>
<summary><strong>📦 Click to View HTML Meta Boilerplate</strong></summary>

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- ✅ Basic Meta Tags -->
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Page Title</title>
  <meta name="description" content="Short description of the page for SEO and social previews." />
  <meta name="keywords" content="html, meta, seo, responsive, web" />
  <meta name="author" content="Your Name or Company" />
  <meta name="theme-color" content="#06c1db" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />

  <!-- 🔁 Optional -->
  <!-- <meta http-equiv="refresh" content="30" /> -->
  <!-- <meta http-equiv="refresh" content="5; url=https://example.com/" /> -->

  <!-- 📲 Social Media -->
  <meta property="og:title" content="Your Page Title" />
  <meta property="og:description" content="Social media preview text." />
  <meta property="og:image" content="https://example.com/image.jpg" />
  <meta property="og:url" content="https://example.com/" />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Your Page Title" />
  <meta name="twitter:description" content="Text for tweet preview." />
  <meta name="twitter:image" content="https://example.com/image.jpg" />

  <!-- 📱 Mobile -->
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
  <link rel="apple-touch-icon" href="/icon.png" />
  <link rel="icon" href="/favicon.ico" type="image/x-icon" />

  <!-- 🔒 Optional Security -->
  <!-- <meta http-equiv="Content-Security-Policy" content="default-src 'self';" /> -->
</head>
<body>
  <h1>Hello, world!</h1>
</body>
</html>
```

</details>

---

## 📘 Explanation of Each Meta Tag

| Tag | Purpose | Example | Notes |
|-----|---------|---------|-------|
| `<meta charset="UTF-8" />` | Defines character encoding. | `UTF-8` | Required for correct text rendering. |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` | Enables responsive design. | Responsive layout | Ensures mobile usability. |
| `<title>` | Sets page title in browser tab. | `"My Site"` | Used in SEO and browser tabs. |
| `<meta name="description" />` | Search engine snippet. | SEO description | Appears in Google search. |
| `<meta name="keywords" />` | SEO keywords (legacy). | `html, meta` | Often ignored by modern SEO. |
| `<meta name="author" />` | Author info. | `Your Name` | For documentation or credit. |
| `<meta name="theme-color" />` | Mobile browser color. | `#06c1db` | Chrome UI tint on Android. |
| `<meta http-equiv="X-UA-Compatible" />` | IE compatibility. | `IE=edge` | Ensures latest rendering mode. |
| `<meta http-equiv="refresh" />` | Auto-refresh or redirect. | `30`, or `5; url=https://...` | Optional. |
| `<meta property="og:*" />` | Open Graph (Facebook, LinkedIn). | `og:title`, `og:image`, etc. | Controls link previews. |
| `<meta name="twitter:*" />` | Twitter Cards. | `twitter:card`, etc. | Rich previews on Twitter. |
| `<meta name="apple-mobile-web-app-capable" />` | iOS app-like mode. | `yes` | Full-screen web app. |
| `<meta name="apple-mobile-web-app-status-bar-style" />` | iOS status bar theme. | `black-translucent` | Affects top bar color. |
| `<link rel="apple-touch-icon" />` | iOS home screen icon. | `icon.png` | Should be 180x180 px. |
| `<link rel="icon" />` | Site favicon. | `favicon.ico` | Shown in tabs and bookmarks. |
| `<meta http-equiv="Content-Security-Policy" />` | Security via CSP. | `'self'` | Prevents XSS. Use carefully. |

---

🔐 **Note:** Some tags (like `refresh` and `Content-Security-Policy`) are optional and should be used based on your use case.