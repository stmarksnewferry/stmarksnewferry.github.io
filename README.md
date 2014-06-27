# Editing the content of the site

Once you have access to this repository, you can just edit the files on [GitHub](https://github.com/stmarksnewferry/stmarksnewferry.github.io). When you save the file (or 'commit it to the repository'), the [real site](http://stmarksnewferry.github.io/) will update by magic.

Most content can be found in the `_posts` directory. Each file corresponds to a box on one of the pages of the site. The category determines where the box ends up, and the boxes are sorted by reverse date (like a blog), where the date is the first part of the filename (the rest of the filename doesn't make a difference, but it's generally `yyyy-mm-dd-category-name-one-or-two-other-words.md`). It's a bit messy, I know, but if you want to change the order in which the boxes appear on one of the pages, you simply need to change the dates in the filenames.

Some content can be found in the `index.md` files, either in the root directory, or in the directory for each page (`about`, `contact`, `whats-on`).

Files ending in `.md` use [Markdown](https://help.github.com/articles/markdown-basics), which makes it easy to format text (bold, italic, lists, etc) and to include links (e.g., `[link text](http://www.example.com)` becomes [link text](http://www.example.com)).

You can upload images to the `img` folder, and then compare other files to see how to include them in the content. It's best to copy the sizes of existing files: 1110x530 for the carousel images on the front page, 750x450 for the pictures of staff members, 1920x1080 for the background, and a width of 360 for other pictures included in boxes.

# Changing the appearance

This is done via the files in `_layouts` and `_includes`. If you want to make significant changes, it's best to experiment on something other than the real site! See below...

# More details

The site is built using [Jekyll](http://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). For major site edits, it's best to install Jekyll properly, and also to get `git` installed (so you can edit the files on your computer).

For the site's appearance, it uses the [Business Casual](http://startbootstrap.com/business-casual) theme, which is built using [Bootstrap](http://getbootstrap.com/).
