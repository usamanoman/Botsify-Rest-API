# Botsify Rest API

Access your WordPress site's data through an easy-to-use HTTP REST API and integrate it easily with Botsify to make your messenger chatbot.


## About

Botsify helps you make chatbots for messenger. With new Botsify REST API, you can build your chatbots for your WordPress site in 1 click. You don't have to be programmer at all in order to make your next chatbot. This rest API is inherited from WP-REST-API plugin.

This plugin is a merger of WordPress Rest API plugin and Better Featured Image plugin.

WordPress is moving towards becoming a fully-fledged application framework, and
we need new APIs. This project was born to create an easy-to-use,
easy-to-understand and well-tested framework for creating these APIs, plus
creating APIs for core.

This plugin provides an easy to use REST API, available via HTTP. Grab your
site's data in simple JSON format, including users, posts, taxonomies and more.
Retrieving or updating data is as simple as sending a HTTP request.

Want to get your site's posts? Simply send a `GET` request to `/wp-json/wp/botsify/posts`.
Update user with ID 4? Send a `POST` request to `/wp-json/wp/botsify/users/4`. Get all
posts with the search term "awesome"? `GET /wp-json/wp/botsify/posts?filter[s]=awesome`.
It's that easy.

WP API exposes a simple yet easy interface to WP Query, the posts API, post meta
API, users API, revisions API and many more. Chances are, if you can do it with
WordPress, WP API will let you do it.

WP API also includes an easy-to-use JavaScript API based on Backbone models,
allowing plugin and theme developers to get up and running without needing to
know anything about the details of getting connected.

There's no fixed timeline for integration into core at this time, but getting closer!


## Installation

Drop this directory in and activate it. You need to be using pretty permalinks
to use the plugin, as it uses custom rewrite rules to power the API.

Also, be sure to use the Subversion `trunk` branch of WordPress Core as there are potentially recent commits to Core that the REST API relies on. See the [WordPress.org website](https://wordpress.org/download/svn/) for simple instructions.

## Issue Tracking

All tickets for the project are being tracked on [GitHub][]. You can also take a
look at the [recent updates][] for the project.

## License

[GPLv2+](http://www.gnu.org/licenses/gpl-2.0.html)

[docs]: http://v2.wp-api.org/
[GitHub]: https://github.com/WP-API/WP-API/issues
[contributing]: CONTRIBUTING.md
[recent updates]: https://make.wordpress.org/core/tag/json-api/
[hackerone]: https://hackerone.com/wp-api
