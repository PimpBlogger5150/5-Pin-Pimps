# The 5 Pin Pimps — free website setup

## Put it online with GitHub Pages
1. Sign in or create a free account at https://github.com.
2. Create a **public** repository named `5-pin-pimps`.
3. Upload all files in this folder to the top level of the repository.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. GitHub will display your website address, usually `https://YOUR-USERNAME.github.io/5-pin-pimps/`. It may take a few minutes to publish.

## Publish a blog post
1. Open your website and click **POST A STORY**, or open `editor.html`.
2. Enter the date, category, headline, teaser and full story.
3. Click **DOWNLOAD UPDATED POSTS**. Your browser downloads `posts.js`.
4. Open your GitHub repository and choose **Add file → Upload files**.
5. Upload the new `posts.js`, replacing the old one, then commit the change.
6. Wait for GitHub Pages to update and refresh your website. Your new post will appear first.

The editor carries forward the existing posts and adds the new one at the top. Keep a backup of the latest `posts.js`.

## Edit roster, Hall of Shame, photos and standings
Edit `data.js` in GitHub (click the pencil icon).
- Change the `roster` names, roles and averages.
- Add or edit `shame` entries.
- For photos, upload image files into a new `images` folder, then put paths such as `images/team-night.jpg` in the `gallery` list.
- Update `standings` with your actual results.

## Notes
GitHub Pages hosting is free for a public repository. A custom `.com` domain is optional and usually costs extra. This is a static website: there is no private login or database. Only people with write access to your GitHub repository can publish changes. Don't publish private information or anything you don't want public.
