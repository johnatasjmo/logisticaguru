# Logistica Guru

## Local server
Start your local server
```bash
npm start
```

Build public folders
```bash
npm run build
```

## Content types
There are two content types blog and itemized.
Blog is used for common blog post.
Itemized is used for a glosary term.

## URLs
Production: https://logistica.guru/
Admin: https://logistica.guru/admin

## Login to create posts
You must be added by admin to get a login, you can use github or gmail and have rights to create posts.

## Media
Media pictures are to be uploaded in "Media" link under admin.
Images are to be aprox `840 × 341` which means to be wider than taller.
Image height must be aprox 300px.

## Content
### Blog
Title:
Author:
Categories:
Date:
Description:
Featured:
Featuredalt:
Linktitle:
Body:

### Itemized
Title:
Author:
Cathegories:
Description:
Featured:
Featuredalt:
Linktitle:
Body:

## Workflow
Workflow has the following steps: Drafts, In Review, Ready.
Only Ready articles can be published.
There are no roles configured, but it will be ok to have an editor role to move articles from In Review to Ready stage and later publishing.

1. First, add the image using the media button.
2. Create a blog/item post and add the image name on the field "Image" (i.e placeholder1.png)
3. Optionally, add images within the body
4. Click on "Save"
5. Mark the post as "Ready"
6. Mark the post as "Published" wait for 1 minute and the post will be published
