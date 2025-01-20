<<<<<<< HEAD
# Phantom Change Log
=======
## Unreleased version
- BREAKING CHANGE: Allow changing the order of the social network links that appear in the footer (#1152)
- BREAKING CHANGE: `google-scholar` social network link no longer requires the prefix `citations?user=`; if you previously set this parameter, it needs to be updated (#1189)
- Added `mathjax` YAML parameter to allow support for MathJax, used to write LaTeX expressions (#195)
- Added explicit support for favicons, you only need to add a `favicon.ico` file to the root directory
- The footer of a page always sticks to the bottom, even on short pages (#576)
- Added `author` YAML parameter to allow specifying the author(s) of a post (#1220)
- Fixed bug where search results broke if a post title had a backslash (#1279)
- Fixed bug where hovering over search results showed the text "{desc}" (#1156)
- Added social network links for GitLab, Bluesky, Whatsapp, Untappd (#1168, #1218, #1299, #1307)
- Support reddit social network link to either be a subreddit or a user (#1371)
- Use CSS variables (#661)
- Added instructions and example on how to fix image links in project sites (#1171)
- Pagination buttons: use nicer arrows, and don't show text on small screens (#1221)
- Updated Yelp URL format - if you previously used the `yelp` social network config parameter, you might need to update the config value (#1259)
- Added `title-on-all-pages` config setting, that adds the website title to all page titles (#1272)
- Change Twitter icon to X (#1193)
- Upgraded font-awesome to 6.5.2 (#1330)
>>>>>>> b1b667e372acf5f602cca6fee64dd850af70f3da

All notable changes to this project will be documented in this file.

# 1.1.2 - Jan 4, 2020
- Fixing symlink error in default layout.
- Update readme install steps.

# 1.1.1 - May 04, 2019
- Update pagination to fix [#14](https://github.com/jamigibbs/phantom/issues/14)

# 1.1.0 - May 26, 2018
- Fix [#6](https://github.com/jamigibbs/phantom/issues/6) & [#7](https://github.com/jamigibbs/phantom/issues/6) to enable pagination
- Conversion to Gem-based theme to fix [#8](https://github.com/jamigibbs/phantom/issues/8)
- Add code formatting and syntax highlighting
- Consolidate configuration to `_config.yml`
- Standardize a few variable names for clarity
- Fix image reference in posts
- Move `about.md`
- Rename _**this**_ file
- Update README as needed

# 1.0.2 - Apr 13, 2016
- Fomspree has been changed to secure connection (https)

# 1.0.1 - Feb 24, 2016
- Fixing Medium button conditional display
- Adding Google Analytics setting

# 1.0.0 - Feb 21, 2016
- Initial release
