# The Ultimate Package
The Ultimate Package is [Erskine Design][]'s framework for rapidly developing the front-end of our projects and is under constant development and improvement by the team at Erskine Design, who use it daily.

## Requirements
A web server to interpret the PHP files in the package, and a browser to render them.

## Getting started
The package is a barebones framework to help you rapidly develop your projects. Create templates using the [Twig template engine][] in `/templates` as you need them and use `/templates/elements.html` to check your styles.

## Before you deploy to production
Firstly, don't forget to remove the following files or folders:

* `/templates/elements.html`
* `/static/images/dev`

Then, the following are also worth considering:

* Update your `/humans.txt` file in the root directory
* Update the holding assets in `/holding`
* Update your `Site Name` in `/templates/base.html` and `/static/css/screen.scss`

## Credits
The project is currently maintained by [Wil Linssen][], [Garrett Winder][] and [Chris Rowe][]. The original Ultimate Package was created by [Greg Wood][].

## License
The Ultimate Package is Copyright &copy; 2012 [Erskine Design][] and is licensed under the [Creative Commons 3.0][] license.

[Erskine Design]: http://erskinedesign.com/
[Twig template engine]: http://twig.sensiolabs.org/

[Wil Linssen]: http://wil-linssen.com/
[Garrett Winder]: http://garrettwinder.com/
[Chris Rowe]: http://chrisrowe.net/
[Greg Wood]: http://gregorywood.co.uk/

[Creative Commons 3.0]: http://creativecommons.org/licenses/by-nc-sa/3.0/