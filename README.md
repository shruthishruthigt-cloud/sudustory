# SuduStory

A responsive, static website for sharing stories and videos.

## Preview locally

Open `index.html` in a web browser. The video section includes a sample YouTube embed and a placeholder for an MP4 file.

## Add your own content

- **Stories:** Edit the story title, date, summary, and link in the `#stories` section of `index.html`. Replace the sample `mailto:` links with links to your story pages or documents.
- **YouTube videos:** Replace the sample video ID in the iframe URL with the ID from your YouTube link, then update its title and description.
- **MP4 videos:** Add a `videos` folder to the repository, upload your MP4 there, and update the `<source src="...">` path if needed.

This is a static site: new content appears for everyone after the updated files are committed and deployed. It does not yet include a sign-in or upload system.
