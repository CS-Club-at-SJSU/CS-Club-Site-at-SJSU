# CS Club @ SJSU Web site

The open-source repository for [http://csclubsjsu.com/](http://csclubsjsu.com/), San Jose State University's Computer Science club.

The github page for this project can be found at [https://github.com/CS-Club-at-SJSU/CS-Club-Site-at-SJSU](https://github.com/CS-Club-at-SJSU/CS-Club-Site-at-SJSU).

## About this project

The site is implemented as a [Jekyll](http://jekyllrb.com/) project. It uses markdown, primarily, to format its pages. The project is still in its infancy and we have not yet identified all of the technologies we wish to use, nor all the functionality we wish to implement.

## How to test the site

Testing the site in a local deployment (not meant for production release) is very simple, almost suspiciously so.

Follow [these very simply instructions (link)](https://github.com/mojombo/jekyll/wiki/install) to install jekyll. (Summary: on most machines, just `sudo gem install jekyll`.) Then, in the root project directory, run:

    $ jekyll --serve

Then point your browser at [http://localhost:4000](http://localhost:4000). It should be running!

## How to contribute

To contribute a change, please fork the [project](https://github.com/CS-Club-at-SJSU/CS-Club-Site-at-SJSU) and hack way! When you've finished comitting your changes, send a 'Pull Request' through github, and the webmaster will review and merge your changes.

Then issue a pull request.

### Adding a new page

In short, to add a new page, you can either just add a file (like 'about.md'),
or you could also run `rake page name='NAME HERE'`. Your call.

### Adding a new post

Currently, posts are not well-supported. You can add one, though, just run
`rake post title='TITLE HERE'`. It will be added and accessible through the
atom feed or the archive, and later on when the front page supports posts it
will be supported there as well.


## About the author

The original project was created by student Erich Blume
< [blume.erich@gmail.com](mailto:blume.erich@gmail.com) > in 2012. Erich claims
the copyright, but has licensed the project under the GPLv3 (see below) so that
future generations of SJSU hackers can use it as they see fit.

### About the oldest-ancestor repo

You might noticed that user 'eblume' holds the oldest repo, despite the fact that the 'canonical' repo is a descendent. This is an artifact of how the project developed. Please do use the [official CSC@SJSU repo](https://github.com/CS-Club-at-SJSU/CS-Club-Site-at-SJSU), and not the oldest-ancestor repo (owned by eblume).

## License

This project is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This project is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this project.  If not, see <http://www.gnu.org/licenses/>.


