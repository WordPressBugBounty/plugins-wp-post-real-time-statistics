=== Real-Time Post Statistics for WordPress ===
Contributors: osamaesh
Tags: statistics, stats analytics, counter, traffic, hits
Requires at least: 4.1
Tested up to: 7.0.2
Stable tag: 3.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html


A lightweight and simple tool to track your post statistics with real insights.

== Description ==
WP Post Statistics is a simple and efficient plugin that helps you track and understand your post performance with clear and useful statistics, including GEO location data.

The plugin gives you a complete overview of how your content is performing, allowing you to monitor visits, visitors, and traffic sources without any complex setup. It is designed to be fast, accurate, and easy to use.

<strong>Single Post Statistics includes: </strong>
<ul>
<li>Comprehensive overview dashboard with countries, cities, visitors, and visits</li>
<li>Compatible with all post types</li>
<li>Track visits and unique visitors over any selected period</li>
<li>Weekly statistics to monitor content performance trends</li>
<li>GEO location tracking (countries and cities)</li>
</ul>

The plugin works instantly after activation and stores all data locally without relying on external services, making it reliable and privacy-friendly.

Perfect for bloggers, content creators, and website owners who want a clear and simple way to monitor their content performance.

== Screenshots ==
1. Posts statistics page
2. Geo Locations page

== Installation ==

The plugin is simple to install:

1. Download `WP-post-real-time-statistics.zip`
2. Unzip the file
3. Upload `WP-post-real-time-statistics` directory to your `/wp-content/plugins` directory
4. Go to the plugin management page and enable the plugin
5. Go to Posts list to view the stats

You can find full details of installing a plugin on the [plugin installation page](http://goo.gl/nf3WcU).

== Changelog ==

= 3.2 =
1. Security: added capability and nonce checks to the analytics AJAX endpoints (first chart, countries table, cities table) to prevent unauthorized access to visitor data
2. Security: hardened the analytics queries against SQL injection using prepared statements
3. Fix: corrected visitor IP address not being recorded on new visits
4. Sends a nonce with the admin analytics requests and bumps the admin script version
5. credit: Artus KG

= 3.1 =
1. check compatibility issues

= 2.9 =
1. including some commonly known bots and crawlers

= 2.8 =
1. check compatibility issues

= 2.7 =
1. CSS fixing

= 2.6 =
1. Fix compatibility issues - part 2


= 2.5 =
1. Fix compatibility issues


= 2.4 =
1. fix php 7 compatibility issues

= 2.3 =

1. Bug fixing in post counter for IPv6

= 2.2 =

1. Fix "Hits per country" order (show top traffic in the begining)
2. Show the total views per country in the graph

= 2.1 =

1. Bug fixing in the plugin activation
2. Fix popup in the new wordpress version
3. PHP 7.x support

= 1.3 =

1. optimize styling

= 1.2 =
1. fix php 7 compatibility issues
2. optimize results