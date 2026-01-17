# CardGen Tools Suite

A professional Card Generator and Validator tool suite with a premium UI, dark mode, and responsive design.

## Features
- **Luhn Algorithm Verification**: Validate numbers mathematically.
- **Bulk Generation**: Generate up to 100 cards at once.
- **Dark/Light Mode**: Automatic and manual theme switching.
- **Responsive Design**: Works on mobile and desktop.
- **Copy to Clipboard**: Easy one-click copy.

## Deployment to Vercel

This project is ready for Vercel deployment.

1.  Push this code to your GitHub repository.
2.  Go to [Vercel](https://vercel.com) and "Add New Project".
3.  Import your `cardgen` repository.
4.  Vercel will detect it as a static site. Click **Deploy**.

## How to Check/Validate
- If the deployment fails, check the "Build Logs" in Vercel.
- Ensure `index.html` is in the root directory.

## Adding Adsterra Ads

There are pre-defined slots in `index.html` for your ads.

**Steps to update ads:**
1.  Open `index.html`.
2.  Search for `<div id="adsterra-...">`.
3.  Paste your Adsterra script code inside the `div`, replacing the comment `<!-- ADSTERRA ... CODE GOES HERE -->`.

**Example:**
```html
<div id="adsterra-sidebar-300x250" ...>
    <!-- Paste your script here -->
    <script type="text/javascript">
        atOptions = { ... };
    </script>
    <script type="text/javascript" src="//..."></script>
</div>
```
