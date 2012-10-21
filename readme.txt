=== Plugin Name ===
Contributors: lkbgift, (1.1) boonebgorges, (1.1) blsci
Tags: add, email, bulk, users, import, buddypress
Requires at least: WordPress 3.0
Tested up to: WordPress 3.3.1
Stable tag: 1.2

Allows blog administrators to add multiple users to blogs at a time. Blog administrator can specify email/username, firstname, and lastname. The display name of an account is set to "Firstname Lastname".

== Description ==

Requires WordPress 3.0+.

Allows blog administrators to add multiple users to blogs at a time, using only a list of email addresses. Now the ability to use the first and last name is added. The display name of an account is set to "Firstname Lastname". When the specified email address matches an existing account, the account will be added as a user on the blog. Otherwise a new account is created and the new user added with the specified role. Based on DDImportUsers.

The plugin determines username automatically from the email address. For example, the email address bgorges100@example.com will produce the email address bgorges100. For that reason, this plugin works best when used in schools or organizations with official, unique email addresses.

When BuddyPress is installed, the welcome email will also include a link to the new user's Edit Profile screen.

This plugin was developed for Blogs@Baruch of Baruch College's Bernard L Schwartz Communication Institute. http://blsciblogs.baruch.cuny.edu

This plugin was modified for ThePearlOnline of Soka University of America.
http://www.thepearlonline.com 

== Installation ==

* Install and activate the plugin through Dashboard > Plugins
* Visit Dashboard > Tools > Import Users to import users

== Changelog ==

= 1.0 =
* Initial release

= 1.0.1 =
* Updated readme to reflect minimum requirements
* Updated readme to contain proper instructions
* Fixed typos

= 1.1 =
* Unhardcoded the text of emails
* Added fields where the sender can modify the content of the email
* Saves the customized email content for future use

= 1.2 =
* Fixed for non-wordpress MP
* Added the function to add First and Last name
* Edited the display name to default to "Firstname Lastname"
