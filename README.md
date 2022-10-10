# Github pages for Jingnan Jia

This academic website repository is cloned from https://github.com/academicpages/academicpages.github.io.

Full setting could be found [here](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).
## How to set the configeration?

Set site-wide configuration and create content & metadata (see below -- also see this set of diffs showing what files were changed to set up an example site for a user with the username "getorg-testacct")
Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
Check status by going to the repository settings, in the "GitHub pages" section
(Optional) Use the Jupyter notebooks or python scripts in the markdown_generator folder to generate markdown files for publications and talks from a TSV file.

## directory introduction
0. File `_config.yml` is used to config the website.
7. [**important**] Directory `_pages` stores the content shown on the main website. The files under it may be used by `_data/navigatioin.yml`. 
1. The files in `_publications` and `_talks` could be generated by `markdown_generator`, but not necessary. I think 
changing the files directly is easier.
2. Directory `files` stores `.pdf` or any other files which may be cited by `publichation` or `talks` or `CV`.
3. Directory `_includes`, `_layouts`, `_sass` and `assets` are not known yet.
4. Directory `_teaching` ?
5. Directory `_posts` contains the posts. But how to show/dis-show them on the main page?
6. Directory `_portfolio` ?
8. Directory `_data`:
    1. File `navigation.yml` config the main parts shown on the main web. This is **very important!**


## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/Jingnan-Jia/Jingnan-Jia.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)
