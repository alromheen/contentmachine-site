# Silent Battles Publisher - TikTok Review Site

This is the public compliance website for the Silent Battles Publisher / ContentMachine TikTok Developer App Review.

## Files To Upload

Upload these files to a public GitHub repository:

- `index.html`
- `privacy.html`
- `terms.html`
- `README.md`
- `.nojekyll`

## App Purpose

Silent Battles Publisher helps users generate short motivational videos and authorize TikTok so the app can upload or publish selected videos to the user's TikTok account.

## Data Disclosed In The Privacy Policy

The Privacy Policy explains that the app may collect or process:

- TikTok basic profile information
- OAuth access and refresh tokens
- Uploaded video metadata
- Captions and hashtags
- App usage logs

It also explains that users can revoke access from TikTok settings and request deletion of their app-related data.

## Manual GitHub Pages Deployment

1. Create a public GitHub repository named:

   ```text
   contentmachine-site
   ```

2. Upload the files from the `tiktok-review-site` folder:

   ```text
   index.html
   privacy.html
   terms.html
   README.md
   .nojekyll
   ```

3. Open the repository on GitHub.

4. Go to:

   ```text
   Settings > Pages
   ```

5. Under `Build and deployment`, select:

   ```text
   Source: Deploy from a branch
   Branch: main
   Folder: /root
   ```

6. Click `Save`.

7. Wait for GitHub Pages to publish the site.

The public URL will usually look like:

```text
https://YOUR_GITHUB_USERNAME.github.io/contentmachine-site/
```

Use these URLs for TikTok Developer App Review:

```text
Homepage URL:
https://YOUR_GITHUB_USERNAME.github.io/contentmachine-site/

Privacy Policy URL:
https://YOUR_GITHUB_USERNAME.github.io/contentmachine-site/privacy.html

Terms of Service URL:
https://YOUR_GITHUB_USERNAME.github.io/contentmachine-site/terms.html
```

## Verification Checklist

Before submitting to TikTok:

- Confirm the homepage opens publicly without login.
- Confirm `privacy.html` opens publicly.
- Confirm `terms.html` opens publicly.
- Confirm the homepage footer links work.
- Confirm the contact email is `alromheen@yahoo.es`.
- Confirm the app description in TikTok Developer matches the homepage.
- Confirm the OAuth scopes requested in TikTok match the app's actual behavior.
