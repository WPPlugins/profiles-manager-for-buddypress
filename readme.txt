=== Plugin Name ===
Contributors: elbuntu
Tags: Buddypress, Profile, Social Network
Requires at least: 2.8
Tested up to: 3.4
Stable tag: 1.1

This plugin is designed to help you monetize your social network by hiding the premium profile fields from non-paying members. 

== Description ==

Profiles Manager is a new version of Elvito BP created by me ages ago. This update supports the newer versions of Wordpress/Buddypress. 
This plugin is designed to help you monetize your social network by hiding the premium profile fields from non-paying members. This plugin
works with any kind of payment system in place but is tested with s2member.

Features:

* Hide premium profile fields from non-paying members
* Easy to use config panel
* Create upgrade account link on free members profiles.

== Installation ==

Requirements:

- Buddypress 1.2.7 or higher.
- Wordpress 2.8 or higher

1. Upload BPM filder to your Wordpress Plugins folder.
2. Go to your buddy-press template and search for edit.php under members/single/profile.
3. Change bp_profile_group_tabs(); with  bp_pm_group_tabs();
4. Activate the Profiles Manager in wp-admin under plugins.
5. Go to settings -> Profiles Manager
6. Your all set!

== Removing the plugin ==

- Deactivate The PLugin 
- Replace bp_pm_group_tabs(); with bp_profile_group_tabs();

== Frequently Asked Questions ==

-- Where is edit.php? --

It is located in your child theme under members/single/profile/edit.php


-- Other Information --

If you are having difficulties getting this plugin to work please email me with the details 
at ashley.gary.johnson@gmail.com or comment on the plugin page.

== Changelog ==

= 1.1 =

* Fixed Bugs with DB Queries

= 1.0 =

* Redeveloped using a fork of Elvito BP
* Updated for newer versions of Wordpress/BuddyPress

<?php code(); // goes in backticks ?>