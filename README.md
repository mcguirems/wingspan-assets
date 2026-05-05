# wingspan-assets

Asset Library README Instructions

This repository stores public image, document, and brand assets that can be linked from Markdown files, websites, documentation, and other public content.

The repository is deployed through Netlify, so every committed file becomes available at a public URL.

Public URL pattern

Base URL:

https://YOUR-NETLIFY-SITE-NAME.netlify.app

Or, if using a custom domain:

https://assets.yourdomain.com

A file stored here:

images/ride-ottawa/example-image.jpg

Can be loaded from:

https://YOUR-NETLIFY-SITE-NAME.netlify.app/images/ride-ottawa/example-image.jpg

Or:

https://assets.yourdomain.com/images/ride-ottawa/example-image.jpg

Folder structure

downloads/
images/
  myvelofit/
  ride-ottawa/
  wingspan/

Recommended file naming

Use lowercase, dash-separated names.

Good:

level-2-camp-fortune-course.jpg
ride-ottawa-logo-black.png
spring-course-guide.pdf

Avoid:

Level 2 Camp Fortune Course FINAL.jpg
Ride Ottawa Logo Black Copy 2.png
Spring Course Guide v3 FINAL FINAL.pdf

Adding a new image or file

1. Open this repository in GitHub.
2. Open the correct folder.
3. Click Add file.
4. Choose Upload files.
5. Drag the file into GitHub.
6. Commit the change to the main branch.
7. Wait for Netlify to redeploy.
8. Copy the public URL using the folder path and file name.

Example GitHub file path:

images/ride-ottawa/how-to-get-more-out-of-your-riding.jpg

Example public URL:

https://YOUR-NETLIFY-SITE-NAME.netlify.app/images/ride-ottawa/how-to-get-more-out-of-your-riding.jpg

Using an image in Markdown

![How to get more out of your riding](https://YOUR-NETLIFY-SITE-NAME.netlify.app/images/ride-ottawa/how-to-get-more-out-of-your-riding.jpg)

With a custom asset domain:

![How to get more out of your riding](https://assets.yourdomain.com/images/ride-ottawa/how-to-get-more-out-of-your-riding.jpg)

Linking to a downloadable file in Markdown

[Download the guide](https://YOUR-NETLIFY-SITE-NAME.netlify.app/downloads/spring-course-guide.pdf)

With a custom asset domain:

[Download the guide](https://assets.yourdomain.com/downloads/spring-course-guide.pdf)

Notes

This repository is intended for public assets only. Do not upload private files, client-confidential files, credentials, exports, financial records, or anything that should not be publicly accessible.

Once a file is committed and deployed, assume it may be cached or copied elsewhere even if it is later deleted.

Keep file names stable whenever possible. If a file is renamed, any Markdown or website links pointing to the old URL will break.
