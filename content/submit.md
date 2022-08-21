---
title: Submit a new blog
---

If you want to submit your blog, or somebody's else, you're very welcome to !

Our only criterias are : a personal or independent blog, regularly updated.

As the directory is humanly curated, each submission will be treated case by case.

## What informations do we need

- The blog name
- The blog URL
- The blog description
- The blog RSS Feed URL (optional)
- The reciprocal link page (optional)
- The category (suggest one if missing)

The reciprocal link page is a link back to us. That's not mandatory to appear on this Blogroll, but the requests who gives a link back will be examinated in priority as a gratitude recognition.

## How-to

### By email

Send the expected inputs by email to `hello` at this website domain.

### On GitHub

You have a GitHub account ? Submit your blog by forking the [Yet Another Blogroll's repository](https://github.com/Wivik/yetanotherblogroll), creating a new branch and pull-request it ! If you have no clue of what this part is talking about, please use the way above.

If you're already a Hugo user, you can fork the repository and create your entry with the following command :

```bash
hugo new <thecategoryfolder>/<yourblogname>.md
```

Then, open `<thecategoryfolder>/<yourblogname>.md` and edit the content according to your blog.

```yaml
---
## Blog name
title: "{{ replace .Name "-" " " | title }}"
## Blog description
description: "You blog description"
## Blog main URL
link: "https://youlink"
## RSS Feed URL (optional)
rss_feed: ""
## Reciprocal link page URL (optional)
reciprocal_link: ""
---
```

If you don't have Hugo, just copy the `archetypes/default.md` file into the folder of your choice, named after your blog, and do the same.

## How much time will it takes ?

`¯\_(ツ)_/¯`

This Blogroll is manually and humanly curated, so it will depend of the amount of requests to proceed at time.

