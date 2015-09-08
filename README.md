# St Mark's New Ferry Website

Once you have access to this repository, you can just edit the files on [GitHub](https://github.com/stmarksnewferry/stmarksnewferry.github.io). When you save the file (or 'commit it to the repository'), the [real site](http://www.stmarksnewferry.org.uk/) will update by magic.

## Editing the content of the site

Content can be found in the directories:

* `_home_boxes` - boxes for the "Home" page
* `_about_boxes` - boxes for the "About" page
* `_team_members` - sections for the team box on the "About" page
* `_whats_on_boxes` - boxes for the "What's On" page

Each file corresponds to a box or section on one of the pages of the site.

To specify the order in which the boxes appear, and to edit some other content, see the respective `.md` files: `index.md` for the home page, then `about.md`, `contact.md` and `whats-on.md` for the other pages.

Files ending in `.md` use [Markdown](https://help.github.com/articles/markdown-basics), which makes it easy to format text (bold, italic, lists, etc) and to include links (e.g., `[link text](http://www.example.com)` becomes [link text](http://www.example.com)).

You can upload images to the `img` folder, and then compare other files to see how to include them in the content. It's best to copy the sizes of existing files: 910x435 for the carousel images on the front page, 750x450 for the pictures of staff members, 1920x1080 for the background, and 360x270 for other pictures included in boxes.

## Extra pages

You can add extra simple pages by clicking the "+" symbol above, to make a new file. Give the file a name like `my-extra-page.md`, and copy and paste what is below into that file (changing the title and permalink, and editing or deleting the `img: ...` line. The page will appear at [http://www.stmarksnewferry.org.uk/my-extra-page/](http://www.stmarksnewferry.org.uk/my-extra-page/). Edit `_config.yml` to specify which pages appear in the navigation bar.

    ---
    title: My extra page
    layout: page
    permalink: /my-extra-page/
    img: my-image.jpg
    ---
    This is a page.

    This is **bold** and this is a [link](http://www.example.com)

## Changing the appearance

This is done via the files in `_layouts` and `_includes`. If you want to make significant changes, it's best to experiment on something other than the real site! See below...

## More details

The site is built using [Jekyll](http://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). For major site edits, it's best to install Jekyll on your computer and [set up Git](https://help.github.com/articles/set-up-git), and then you can edit the files on your computer and test it out before making changes to the real site.

For the site's appearance, it uses the [Business Casual](http://startbootstrap.com/template-overviews/business-casual/) theme by [Start Bootstrap](http://startbootstrap.com/), which is built using [Bootstrap](http://getbootstrap.com/). The theme is Copyright 2013-2015 Iron Summit Media Strategies, LLC, and is released under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).
