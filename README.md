## Introduction

`australiatamilarts.org` is hosted as a [github page](https://pages.github.com/) and powered by [Jekyll](https://jekyllrb.com/docs/quickstart/). Any changes to the site are compiled and rendered as static html thereby serving it as a normal HTML/CSS page to the end-user.

The repository that governs the site is [au-ta.github.io](https://github.com/au-ta/au-ta.github.io) and user access can be granted on need basis.

## Layouts

The site is broadly divided in to two layout files. They are html files and housed under the `_layouts/` folder. The `default.html` governs the home page and the `events.html` governs the events page.

The home page is divided in to *5 sections*, namely, `About`, `Chapters`, `Events`, `Get started` and `Contacts`.

These sections in turn get their content from [markdown](https://guides.github.com/features/mastering-markdown/) content available from `_includes/` folder.

 File           | Section
----------------|---------------------
about.md        | About section 
chapters.md     | Chapters section 
events.md       | Events section 
get_started.md  | Get started section 
contact.md      | Contact section 

The separate `events` page gets its content from the root level `events.md` markdown file.

## Editing using markdown syntax

Markdown files are the inverse of markup files in the way they declutter text from the markup content surrounding them. The Editor should be concerned about basic formatting rules associated with markdown files. They can refer to the following link:

[Markdown guide](https://guides.github.com/features/mastering-markdown/)

In order to edit the concerned markdown file, the logged-in user with appropriate permission to edit the `au-ta.github.io` repository, can visit the concerned folder and click on the `pen icon` :black_nib: (edit link) and edit the file. Once edited, they can use the `preview tab` to preview the changes. The changes with preceding `red marker` indicates lines being `removed` and lines with preceding `green marker` indicates lines being `added`.

Once the Editor is happy with the set of changes, they can save the changes. It takes about a minute or two to automatically compile and render the changes. You can visit the [australiatamilarts.org](http://australiatamilarts.org) site and see if the changes are reflected.

## Slideshow

Slideshow has been enabled by on the following sections in the home page:

- About
- Chapters
- Events

New images can be uploaded or existing images can be deleted by visiting the `images/home/` folder and choosing the appropriate sub-folder `about/` or `events/` or `chapters/`. Any changes made to these images folder should be saved and a minute or two be allowed to reflect the changes on the site. The slideshow will automatically include or exclude the affected image.

The separate `Events` page is meant to embed images inline and please refer to the markdown editing link on how to include inline images.

## To be added

Support social media embedding links and simplify their embed operation

To get started visit the [markdown editor page with preview](https://kramdown.herokuapp.com/).
