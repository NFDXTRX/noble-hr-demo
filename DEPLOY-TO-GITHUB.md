# Publish the mockup using your work GitHub

This site needs no software installation, build command, secret or API key.

## 1. Choose the owner and address

Sign in to your **work GitHub account**. Create the repository under your approved work organisation if you want the organisation name in the address.

Use the repository name `noble-hr-demo`.

A standard project address looks like:

`https://<work-organisation>.github.io/noble-hr-demo/`

GitHub includes the owner login in this address. The repository name alone cannot hide a personal owner login. If your work login contains your name, use an approved organisation or an approved custom domain instead. The files contain no personal account address.

## 2. Create an empty repository

1. In GitHub, select **New repository**.
2. Choose the correct work owner.
3. Enter `noble-hr-demo` as the repository name.
4. Use the visibility allowed by your organisation. GitHub Pages is available for public repositories on GitHub Free. Private repository support depends on the plan and organisation settings.
5. Create the repository. No template is required.

The Pages website may be publicly accessible even when its source repository is private. This package is a fictional demonstration only.

## 3. Upload the website

1. Unzip `Noble-Foods-HR-Website-GitHub.zip` on your computer.
2. In the repository, choose **uploading an existing file**, or **Add file > Upload files**.
3. Upload the **contents** of the unzipped folder, including the logo and image files.
4. Make sure `index.html`, `style.css` and `app.js` appear directly in the repository root. Do not nest them inside an extra folder.
5. Commit the uploaded files to `main`.

The optional `.nojekyll` file may be hidden on your computer. The site works without it because this package does not use a Jekyll theme or underscore-prefixed asset paths.

## 4. Enable GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages** under **Code and automation**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select **main** and **/(root)**.
5. Select **Save**.
6. Wait for the Pages deployment to finish. GitHub will show the published address on the same screen. You can also check the build in **Actions**.

If Pages is missing or blocked, your work GitHub administrator may need to enable it or confirm the plan permits it. Do not change organisation-wide settings to work around this.

## 5. Check and share

Open the published link in a separate browser or signed-out window.

Check that:

- The Noble Foods logo and supporting image appear.
- **Load example** fills a request.
- Review and submission create a fictional ticket.
- HR can assign, reply and resolve.
- Switching to the employee view hides the private note text from the conversation screen.
- The CSV reporting download works.

Copy the exact published address into your email to the team. Each visitor gets their own demo data, so people can explore without altering anyone else's session.

Suggested accompanying wording:

> Here is a working mockup of how the proposed HR ticketing system could work. You can try submitting a request, then switch to the HR view to see how the team would manage it. It uses fictional information and is not connected to our live systems. Please have a click through and note any fields or steps we would need to change.

## Future updates

Replace the changed files in the repository and commit to `main`. GitHub Pages will publish the update automatically. Browser refresh may be required to see the new version.

## Official GitHub instructions

- Creating a Pages site: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Publishing from a branch: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
