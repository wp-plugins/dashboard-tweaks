=== Dashboard Tweaks ===
Contributors: senlin
Donate link: http://senl.in/PPd0na
Tags: dashboard, tweaks, admin bar, toolbar, menus, functions, styles
Requires at least: 3.3-beta4
Tested up to: 3.3
Stable tag: 1.0

A collection of Dashboard Tweaks that enables website developers to customize the WordPress Dashboard more towards their clients.

== Description ==

With the arrival of WordPress version 3.3 the WordPress Dashboard once again received an overhaul/makeover. The tweaks we have been using since 3.2 no longer cut it and that inspired me to develop this plugin for <strong>WordPress version 3.3 or higher</strong>.

I have not included an options panel as this plugin is catered to developers and you are meant to play around with it. If you don't develop WordPress websites for clients, then most likely you won't have much use for this plugin and if you do, then be prepared to roll up your sleeves and get your hands dirty.

A list of the tweaks included in the Dashboard Tweaks plugin:<br />
- change the WordPress logo in the top-left of the admin bar with a custom admin logo<br />
- link that logo to the home URL instead of the new wp-admin/about.php<br />
- remove the entire sub-menu with links to Codex, forums and what not<br />
- remove the Visit Site sub-menu under the site's name<br />
- change "Howdy" into "Welcome back"<br />
- add a special favicon for the Dashboard only (ideally different from the frontend, but up to you)<br />
- change the tab title into a standard "Dashboard of [sitename]"<br />
- remove icons in front of Dashboard menus<br />
- reduce page heading size<br />
- remove publish icon of Add new Post/Page screens<br />
- add colored background to sidebar active sub-menu to add contrast<br />
- add colored background to activated plugins to add contrast<br />
- add custom footer text

The plugin comes localized for use on sites other than the English language and/or on bi/multilingual websites.

== Installation ==

The Dashboard Tweaks plugin requires WordPress 3.3-beta4 or higher.

1. Upload `dashboard-tweaks.zip` to the `/wp-content/plugins/` directory
2. Edit the files `dashboard-tweaks.php` and `/css/wp-admin.css` to your liking (link: `/wp-admin/plugin-editor.php?file=dashboard-tweaks/dashboard-tweaks.php`). See below what can be changed on which lines.
3. Alternatively you can unzip the file on your computer, do your edits and then upload the entire directory `dashboard-tweaks` to the `wp-content/plugins/` folder.
4. Activate the plugin through the 'Plugins' menu in WordPress and enjoy your customized WordPress Dashboard!

Change images for admin favicon and dashboard logo:<br />
Use FTP to upload your own images, the admin favicon is called `dashboard.png` and the dashboard logo is called `adminbar-logo.png`; both files are located in the images folder of the dashboard-tweaks folder.

Which lines of `dashboard-tweaks.php` can be edited?<br />
lines 76-84: change Howdy to Welcome Back<br />
lines 86-91: change tab title text<br/>
lines 93-97: change custom footer text

Which lines of `/css/wp-admin.css` can be edited?<br />
lines 10-11: hover background color for admin-bar-wp-logo<br />
line 17: change page heading size<br />
line 24: change colored background to activated plugins to add contrast<br />
lines 27-28: change colored background to sidebar active sub-menu to add contrast

== Frequently Asked Questions ==

= On the front-end the WordPress stuff in the admin bar is still visible! =

Disable the admin bar for the user when viewing the site. Most clients want to see their own website, not that ugly admin bar.

= Are you planning to add an options panel? =

Maybe. I don't expect (frequent) updates will be necessary for this plugin, so basically your edits are protected.

== Screenshots ==

1. Dashboard after installation (This screen shot description corresponds to images/screenshot-1.jpg).
2. Plugin screen after installation (This screen shot description corresponds to images/screenshot-2.jpg).

== Changelog ==

= 1.0 =
* First version (stable)

== Upgrade Notice ==

= 1.0 =
First release
