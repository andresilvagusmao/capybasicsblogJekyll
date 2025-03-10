# capybasicsblogJekyll
## Run locally
- bundle exec jekyll serve
## Make new posts
- Create a new file in the folder _posts with the naming (YYYY-MM-DD-name.html)
- Inside the file Start it with the following boileplate:

---
**layout: custom_post** (which layout will be used - no change)
**title: "Hello World"** (Sets the title of your blog post Appears in the browser tab, post listings, and at the top of the post)
**date: 2024-08-17 00:00:00 +0000** (Sets the publication date and time of the post Used for sorting posts and URLs)
**author: "André Silva Gusmão"** (Specifies the post author
Appears in the post metadata and is used for SEO
Used by your template to display author information with profile picture)
**description: "My First Post"** (Provides a brief description of the post
Used in post previews, SEO, and social media cards
Appears as italic text under the post title)
**video_id: "vMVVXpbIbhU"** (Optional field for YouTube video integration
Contains the YouTube video ID (the part after v= in YouTube URLs))
**excerpt_separator: <!--more-->** (This is used so in the html of the post you can separate the begining description part that will be in the main page for each post from the post itself.)
---
