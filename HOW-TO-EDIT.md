# How to edit the Gracie & Martins Partners website

Every change you make here goes live on gracieandmartins.com within about two minutes. GitHub keeps a full history, so any change can be undone.

## Changing wording on a page

1. Open the folder for the page. Home is the file `index.html` at the top. The other pages are in folders: `about`, `services`, `approach`, `contact`, `privacy` and `blog`, each holding a file called `index.html`.
2. Click the file, then click the pencil icon at the top right of the file.
3. Find the sentence you want to change. Words sit between tags that look like `<p>` and `</p>`. Change only the words. Leave everything inside the angle brackets `< >` and the curly brackets `{{ }}` and `{% %}` exactly as it is.
4. Click **Commit changes**, add a short note such as "Updated About wording", and click **Commit changes** again.

## Publishing a blog post

The Blog link appears in the menu automatically once the first post is published.

1. Open the `_drafts` folder and click `example-post.md`. Copy all of its text.
2. Go back to the `_posts` folder. Click **Add file**, then **Create new file**.
3. Name the file with the publication date first, then the title in lowercase words joined by hyphens, ending in `.md`. For example: `2026-11-03-why-positioning-comes-first.md`. The date in the name becomes the date shown on the post.
4. Paste the copied text and replace the example wording with your post. Keep the three hyphens and the `title:` and `summary:` lines at the top.
5. Click **Commit changes**.

Inside a post, leave an empty line between paragraphs. Two hash marks and a space at the start of a line (`## Like this`) make a heading.

## Taking a post down

Open the post in `_posts`, click the three dots at the top right, and choose **Delete file**.

## Undoing a mistake

Click **Commits** near the top of the main page to see every change. If something breaks, send Claude the file and describe what happened.

## Files to leave alone

`_layouts`, `_includes`, `assets`, `_config.yml` and `CNAME` control the design and the domain. Change these only with help.
