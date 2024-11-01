=== Plugin Name ===
Contributors: WpGetReady / Fernando Zorrilla de San Martin
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KZPB2M355392Q

Tags: stats, statistics, widget, admin, sidebar, visits, visitors, pageview, referrer, spy, multisite, traffic

Requires at least: 3.3

Tested up to: 3.6.1 

Stable Tag: 1.7.70

License: GPLv2 or later

Real Time Statistics on your blog, collecting information about visitors, spiders, search keywords, feeds, browsers, OS and more.

== Description ==
-----------------

**StatComm** provides realtime statistics on your blog multisite or singlesite, collecting information about visitors, spiders, search keywords, feeds, browsers, OS and more.

Once the plugin has been activated, it will start collecting information.

**StatComm** provides many views to analyze the incoming visitors, including spy tools to find out their procedence. For users of other StatPress plugins variations, it provides a well known feature set and information.

Thank you for use this plugin. If you like it, please rate it!!!
or <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KZPB2M355392Q](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KZPB2M355392Q">make a donation!!!</a>

Drop a note on the forum(s) about what would you like to be improved/fixed.

Current version includes:
-------------------------

 * Multisite support
 * Instant user information + Google Maps (Instant Spy Tool)
 * User Agent Database + Ip tracking through Maxmind database
 * Error page detection (404/403 errors)
 * Custom actions (see code examples on http://wpgetready.com/2012/05/expanding-statcomm-statcomm_info-action/)
 * Custom filter method for control/suppress/modify data saved on database.
 * Migration tool from unsupported Statpress plugins.
 * Subplugins: embedded functionality that administrators can control by enabling/disabling.
 * Error report day by day (activating Error Report subplugin)
 * Shortcodes (activating the shortcode subplugin)
 * Exporting data

Credits
-------
The following users contributed to make these version fixed and/or improved:
##1.7.70

* Tahlia: problem when migration. Fixed incorrect link to migration page.
* <a href="http://wordpress.org/support/profile/bamajr">bamajr</a>: Improved documentation
* Many fixes when the plugin is under strict PHP environment setting
* Fixed compatibility issue with WP 3.6.1 which throwed an error under subplugin page.

##1.7.68

* <a href="http://wordpress.org/support/profile/mdunham">MDunham</a>:  Unexpected multisite behavior

##1.7.67

* <a href="http://wordpress.org/support/profile/germankiwi">GermanKiwi</a>:   Suggestions to improve banip.dat relocation and repeated code
* <a href="http://wordpress.org/support/profile/mdunham">MDunham</a>:  Detected multisite problem, corrected in this version
* <a href="http://wordpress.org/support/profile/ambrosemugwump">AmbroseMugwump</a>: Plugin crashed site if you were trying to install on older WP versions
* <a href="http://wordpress.org/support/profile/fisherofer">Fisherofer</a>:  Plugin unable to detect new networksite, solution to be implemented.
* <a href="http://www.dementiatoday.com">Dementia Today</a>:  Feedback for a problem related to hosting service
* <a href="http://pumka.net/">Anton Oliinyk</a>: Detected and fixed conflict on the  <a href="http://wpempirebuilder.com/">Empire Builder</a> plugin (<a href="http://www.georgekatsoudas.com/">George Katsoudas</a>) 


Version 1.7.70: What is in it for you?
--------------------------------------

* Improved code. Some fixes when Strict PHP is enabled
* Small documentation glitch fixed. Thanks to bamajr
* Bug on the migration menu. Fixed.
* Fixed compatibility issue with WP 3.6.1 which throwed an error under subplugin page.

---

* Please be sure to read the Help provided with the plugin to review the new features, and also the discussion on the blog.
* The Help included contains technical information and tips.
* Support: <a href="http://www.WpGetReady.com">WpGetReady.com</a>
* Forum  : <a href="http://forum.WpGetReady.com">WpGetReady forums</a>

== Installation ==
------------------

* Go to Plugins > Add New for searching plugins
* Search for StatPress Community
* Click on Install Now under StatPress Community
* Be sure that def folder has set to write (777)
* Activate it. The StatComm menu will appear near the bottom of the admin page. The plugin starts collecting when you activate it.
* Customization? Go to the Options page

Important note: I made extensive efforts to a plugin which does not conflict with any Statpress versions or any other plugin. Moreover, this plugin should be running fine side by side with ***any*** Statpress alternative(although not recommended)

== Frequently Asked Questions ==
--------------------------------

>### Where StatComm comes from?

**StatComm** is a complete rewrite of StatPress statistics plugin providing a way to migrate your data from many unsupported StatPress plugins variations.

A detailed milestone is provided on the main site on the <a href="http://wpgetready.com/2012/03/statcomm-roadmap/">Roadmap</a>.
**StatComm** is currently under development.

>Support: <a href="http://www.WpGetReady.com">WpGetReady.com</a>

>Forum  : <a href="http://forum.WpGetReady.com">WpGetReady forums</a>

>###Is there any consideration for install the plugin?

Since version 1.6.3, Statcomm needs that the **def** folder under the installation plugin folder to be **writable** (777). The folder is used to handle Maxmind database updates and files to detect OS. These features can be disabled from the Option pages.

>###Is it multilanguage?

Yes, but keep in mind that currently only English and Spanish are up-to-date. Any who wants to contribute with translation will be awarded with a mention on the plugin.

>###Where can I get help?

* Please visit the <a href="http://www.WpGetReady.com">WpGetReady site</a> for news and plugin insight, and also
the <a href="http://forum.WpGetReady.com">WpGetReady forum</a> the place for plugin support.
The plugin also includes a help reference to starters and important information on advanced topics.

>###Where is the information stored?

Statcomm information and settings are stored in three places in order to work properly:

* few options in the option table. In multisite mode saves data on sitemeta table, single site in options table.
* a database table (**statcomm** postfix)) where all the information about incoming user/agents is stored. On multisite environments the plugin will use one table per site using the plugin.
* plugin-location/def folder, where the user agent information is stored, also banned ip tables.
* all settings are suffixed with statcomm even those generated by subplugins.

>###Is there an uninstall?

* The current release provides an uninstall, cleaning all the options stored when uninstalling. Optionally you can also delete the data table, this options is available in the Advanced Tab.
* The uninstall works for single and multisite wordpress installations, table deletion included.
* In multisite mode **only the Network admin** is capable of uninstall the plugin and optionally delete all the tables.

>###How can I migrate my data from version of [Statpress plugin variation here] to **StatComm**? =

* A migration tool is provided from version 1.7.01. Also, <a href="http://wpgetready.com/2012/06/migrating-from-statpress-plugins-to-statcomm-a-how-to-guide">there is a procedure</a> where it is explained how to migrate data from some unsupported statistics plugins.
These tools has been updated to work in some problematic or outdated hosts.

>###Are you providing support for other Statpress plugin variations?

* If you are using different older/unsupported Statpress variations, **StatComm** is the way to go , since this plugin includes all the enhancements of older an outdated Statpress version/variations. We don't provide support for those plugins.

>###I cannot download the Maxmind database. I'm getting error 403

* Your ip was blocked due too much attempts to download the database or Maxmind site is banning due excess of demand. You should to try later or download it manually from http://geolite.maxmind.com/download/geoip/database/GeoLiteCity_CSV/ and then upload it to the def plugin folder. After that, be sure to activate it from the plugin option panel.

>###Is there any considerations with Multisite mode?

* We tested the multisite mode using subdomain configuration only. See <a href="http://codex.wordpress.org/Before_You_Create_A_Network">before you create a network</a>
* Be aware the multisite mode using different paths is currently **untested**.
* Some options are only available for Network Administrators in a page menu on the Network admin console:

>* UA Parser database install
>* Maxmind database install
>* Optionally delete tables on uninstall.
>* Subplugin control for network administrators (Version 1.7.30 and up)

== Screenshots ==

1. Overview Page + Instant Spy + Google Maps (Ajax Feature)
2. Details Page
3. Spy feature
4. Subplugin Options

== Changelog ==


V1.7.70     (2013-10-05 14:04 -3GT)

* Fixed incorrect link to migration page.
* Improved documentation
* Many fixes when the plugin is under strict PHP environment setting
* Fixed compatibility issue with WP 3.6.1 which throwed an error under subplugin page.


V1.7.69     (2013-10-03 12:35 -3GT)

* Skipped

V1.7.68		(2013-07-06 16:16 -3GT)

* Improved setup conditions before installation
* Reapplied a missing fix from the previous version

V1.7.67     (2013-06-21 19:07 -3GT)

* Few fixes and refactoring.
* Custom banip file is accepted or ignored if is no banip.dat file.
* Re-fix from multisite fix introduced on V1.7.66. Multisites should work normally now
* Help page incorrectly adressed. Fixed

V1.7.66     (2013-06-05 17:15 -3GT)

* Important last minute bug fix     : change of global variable affected adversely multisites. Found by Anton Oliinyk working on Empire Builder plugin (George Katsoudas plugin)

V1.7.65     (2013-06-03 10:50 -3GT)

* Bug fix: Found by mdunham         : Object of class statcommCurrentUser could not be converted to string, happening on some PHP Versions.
* Bug fix: Found by AmbroseMugwump  : Fatal error: Call to undefined function deactivate_plugins() , produced when trying to install plugin on older WP versions
* Bug fix: Found By GermanWiki      : hardcoded path doesn't allow move plugin to other folder.
* Bug fix: Found by GermanWiki      : plugin tree is repeated
* Important last minute bug fix:      change of global variable affected adversely multisites. Found by Anton Oliinyk working on Empire Builder plugin (George Katsoudas plugin)

V1.7.62     (2013-02-09 21:00 -3GT)

   * Suppressed navigation client page (obsolete) since UAS detect all the missing browsers.
   * Minor improvementes
   * Removed obsolete code

V1.7.60     (2013-02-24 12:00 -3GT)

* Metaboxes on the overview: drag, shrink & expand every module on the view.
* Fixed an incorrect url reference on uaparser service.
* Fixed problem with gethostbyaddr
* Added reverse proxy fix http://wordpress.org/support/topic/plugin-statcomm-statpress-community-multisite-edition-correct-ip-address-behind-reverse-proxy? Thanks to rogst
* Shortcodes subplugin
* Maxmind database can be enabled/disabled manually on single and multiste environments
* User Agent String database can be enabled/disabled on single and multisite environments.
* Fixed few glitches on subplugin tabs.
* Added Service authentication on both sides of SAAS service.
* Reports reconfigured dynamically if user enable or disable Maxmind/UAS databases.
* Translation to Spanish up to date.
* Fixed incorrect link when downloading Maxmind on Multisite environment
* Fixed: url are now correctly decoded in every view.
* Improved: UAS database improved checking and better feedback when Statcomm is outdated.
* Improved user permission management. Only administrators has plugin control. Other user are read-only enabled.

V1.7.50     (2012-08-26 10:07 -3GT)

* Fernando Zorrilla: I will manage the whole plugin from now on while my collegue(s) started another projects.
* Extended template system to allow javascript and css run independent for each module.
* First AJAX test were very promising. Even though this version won't show any Ajax module.
* Improved safe_ini mode evaluation. That should fix the button migration is disabled when a statpress table is present.
* Improved error control when Multibyte String Extension is not installed on Apache Server.
* Improved running Statcomm behind proxies. Code improvement thanks rogst (See <a href='http://wordpress.org/support/topic/plugin-statcomm-statpress-community-multisite-edition-correct-ip-address-behind-reverse-proxy' target='_blank'>this link</a>)

V1.7.41     (2012-07-30 23:08 -3GT)

* Fix MaxMind error when opening caused display warnings on top of the site.Fixed.
* Improved Report error now with correct graphics.


V1.7.40     (2012-07-24 22:32 -3GT)

* Improved: Statcomm handles corrupted Maxmind databases with status info and also a chance to repeat download.
* Fix: Cache system incorrectly cached today results, freezing current numbers.
* Faster: In our slow server, the overview is rendered in two seconds. Better times are expected in normal servers.
* Fix: Uninstall in multisite mode delete tables correctly.
* Fix: Subplugin feature now enables user with lower level access correctly.
* Fix: Error counter now matches error report page.

V1.7.31     (2012-07-17 13:11 -3GT)

* Fixes to save data procedure.
* Fix to spy window.

V1.7.30     (2012-07-15 18:18 -3GT)

* New: Added Mustache as template system. It improves the code and makes a clean separation between data and HTML.
* New: Subplugin factory. It works in single and multisite installation.
* Added: Subplugin tab for controlling subplugins. Network administrator will have its own subplugin page.
* Added: Subplugin: Error report. Links graph chart with errors reported in any day.
* Improved: Rewritten mysql class. Discarded interceptors, PHP wasn't made to use overload...300 lines saved.
* Improved: Improved migration, detecting special sites.
* Fix: current error miscalculation corrected. The numbers are updated
* Fix: some queries returned incorrect results.
* Fix: Migration improved and fixed. Validation added, using views, faster and working as expected.
* Warning: Due the changes, Statcomm now needs WP 3.3 and up.

V1.7.20     (2012-06-24 13:10 -3GT)

* First release of Multisite version
* Simplified data handling for Maxmind and User Agent parser.
* Included Network admin page for settings.
* Optionally delete table(s) on uninstall (single and multisite mode).
* Tabbed option interface
* In some hosts, table creation is disallowed or limited. The plugin does it best to detect such condition.
* Fix: displays 'Settings saved' message when any settings is modified.
* Improved: if the plugin is unable of downloading Maxmind database, an extended error detail is displayed.
* Improved: unknown country/ip displays  flag of unknown (a question mark ?).
* Improved: export data added missing fields.

V1.7.10     (2012-06-08 12:00 -3GT)

* Lazy cache: queries and most results are cached, improving the performance while the plugin is used.
* Query counter: you know how many queries does this plugin makes and also how many caches.
* Improved table database design that will be reflected in a performance boost.
* Improved performance: 10x (approx.). Typical time should be under five seconds or less to see 50 columns with 200k records.
* Added error pages information in the graphic view (in red)(activate it from options)
* Added extended information in the graphic view. Hover the graphic's date to see a resume day by day
* Improved migration procedure, detecting set_time_limit disabled on some servers.
* Fixed: plugin avoids to load styles and javascript to other pages in the admin dashboard.

V1.7.01     (2012-06-02 0:00 -3GT)

* Little gap with plugin version. Corrected

V1.7.00     (2012-06-01 0:00 -3GT)

* Migration tool: allows to migrate from outdated Statpress versions
* New filter added: now you can control/filter/exclude/modify what the plugin saves to the database.
* Improved action to control your site traffic
* Language detection (this is different of country/ip detection)
* Fixed problem with characters in main view

V1.6.90     (2012-05-20 9:40 -3GT)

* Recording error pages (404)
* Statcomm extensibility: Now you can control your site traffic with statcomm_info action
* Instant spy: Google Maps
* Overview now has process time in the footer.
* Fixed minor problem with Last Spiders icons
* Instant spy: improved messages when no data.

V1.6.81     (2012-05-13 10:42 -3GT)

* UAS Database off, disabling Browser and OS detection. Fixed.

V1.6.80     (2012-05-12 17:00 -3GT)

* User Agent String Database download procedure provides more user control and it is more manageable.
* Fix an undeclared variable in the capture data affecting some installations
* Fix automatic download issue in some Wordpress tweaked installations.

V1.6.70 	(2012-05-06 21:41 -3GT)

* Sprite optimization: Operative Sytem and Browser icons has been 'sprited'. Average request was improved in a 60% in the tests.
* The sprite conversion eliminates the use of 434+73-2 images= 503 (!). Folder images browser and os supressed
* Instant Spy Tool: hover the IP on the Last hits view to turn on this tool. It will provide instantly with useful information from current user.
* Instant Spy Tool and Spy Tool option can be configured from options.
* Added qTip2 to the current tools (http://craigsworks.com/projects/qtip2/)
* Spy tool moved a new class and improved. Now it depends on maxmind database. (You should have enabled the Maxmind database to make it work).
* Some refactoring took place to handle the same standard. In progress.
* Fixed bug when saving user data
* Spanish translation update (other languages would need an update)

V1.6.60		(2012-04-28 17:45 -3GT)

* Maxmind Geoiplocation. Combined with the uaparser class, StatComm provide one of the most accurated and complete information from visitors. Next versions will take full advantage of these combined features.
* Country flags using CSS sprites to minimize request. 
* Maxmind GeoLiteCity download and activation/deactivation
* Dynamic class load: if Geolocation is disabled, all the related classes are also disabled, keeping the plugin as lightweight as possible.
* Dynamic tables depending of Geolocation enabled/disabled
* Improper spider detection lead in incorrect last hits results. Workaround until 1.6.70
* Incorrect translation prefix. Corrected. Translation should work
* Spanish translation up-to-date, taken as reference to check if every text is translated.

V1.6.52		(2012-04-25 21:00 -3GT)
* This version does not present any major changes, except a change of links to resolve some trademark issues. Wordpress is asking that every author with a domain who has the text 'wordpress' in it (like wordpressready.com) to change the links to a domain name that does not conflict with Wordpress trademark.  Future support and blog will be on www.wpgetready.com (to be enabled this weekend 2012-04-29)

V1.6.50		(2012-04-21 20:40 -3GT)

* User agent service database improved: refresh period ,enabled/disabled feature
* Statcomm warns if you are trying to install in WP3.0 or less.
* Introduced: status panel to check if everything is in order.
* Improved: uninstall option. Current version delete options settings, but does not delete table.
* Introduced file log library in utilities class. enabled/disabled with LOG_FILE_DEBUG const
* Help updated
* Fixed: replaced < ? and < ?= by < ?php which caused problems on some hosts.
* Fixed: user can't set capability to higher level that its own.

V1.6.4(0)	  (2012-04-15 21:15 -3GT)

* Few deprecated functions deleted/resolved/updated/optimized
* Around 50 warnings resolved. The plugin should work without errors even setting debug=true
* Many minor glitches solved.
* New Setting API class override older code. This would allow a easier improvement and follow WP developing recommendations.
* Setting capabilities simplified: You can choose from Super Admin, Administrator, Editor, Author,Contributor & Suscriber.
* Improved Last Search Terms view
* Fix: bad delimiter in regex expression solved.
* New class utilities to collect static methods shared between classes.

V1.6.31   (2012-04-10 12:00 -3GT)

* replaced ereg with preg_match
* Fixed download location of user agent database.
* Until the next version (1.6.4) database download is disabled. Current version could end up locking the user ip, if the
traffic is high so we decided to implement an improved one. Nonetheless, accuracy is up to date.

V1.6.3  (2012-04-08 12:45 -3GT)

* Replaced .dat system file for more reliable and accurate uasparser
* Replace outdated eregi function by preg_match
* Improved file and folder filtering. Tables turned obsolete: os.dat,browser.dat,spider.dat .Exception:banip.dat.
* Searchengines.dat obsolete, replaced by searchterm.ini
* Implemented a new way to get search terms from referrer. We hope is an improved one.
* Improved: icons OS and Browser
* Improved: hovering on page take shows complete link
* Improved: link on page take you that page in a new tab.
* Improved: class mysql returns number of records (getResult only)
* Improved: avoid to use accidentaly properties from the mysql class (currently mysql has NO properties	,only methods)
* Fixed: bug on spy navigation system, although spy feature has to be improved (a lot!)
* Improved: method iriGetSpider obsolete(implies also spider.dat obsolete)
* Fixed: Search didn't redirect to the correct page.

V1.6.2 (2012-04-03 12:00 -3GT)

* No V1.6.1. The amount of changes amerit a version jump ahead.
* Menu compatible with WP 3.0 and up.
* Simplified and deleted menu redirection (no longer needed)
* Cleaner oriented to classes.
* Added class to control database queries.
* Improving documentation
* Renewed widgets. Now extending class WP_Widget, compatible with WP 2.8+
* Widget Print revamped. Now with help.

V1.6.0 First Release (2012-03-23 06:34 -3GT)

* Conversion to OOP (Object Oriented Programming)
* Heavy refactoring: no more prefixes all around.
* First-stage documentation towards Javadoc standard (work in progress).
* First round bug-squashing.
* First round deprecated-code clean.
* Recode to avoid conflicts with other Statpress versions/variations.

== Upgrade Notice ==

Metaboxes & few fixes.