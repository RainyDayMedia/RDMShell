RDMShell
============

This is a starter theme for Wordpress based on `_s` but with a few added features for the RDMWorkflow. This is to quickly start client projects with support for child themes. Though `_s` is not meant to be used with a parent/child theme RDM is modifying it to do this. This will be the bases of the future Frigoris _(an HTML5 Boilerplate and CSS Reset)_.

<strong>This is an active work in progress</strong>

---

###### If you want to pull in the latest version:

1. fork it
2. clone it
	* `git clone https://github.com/YOUR-USERNAME/RDMShell`
3. install node components
	* `npm install`
4. install bower components
	* `bower install`
5. build the next Wordpress __BAMF__!
	* `gulp`
6. add the RDMShell to your __upstream__:
	* `git remote add upstream https://github.com/ginfuru/RDMShell`
7. verify the upstream repo has been added
	* ` git remote -v`
8. then __fetch__ the latest changes the RDMCrew has made:
	* `git fetch upstream`
9. then __merge__
	* `git merge upstream/master`

---

#### To Do:
- [ ] Add Advanced Custom Fields as required
- [ ] Add custom plugin for Custom Post Types _(make it required)_
- [ ] Add support of child themes
- [x] Add Bower support
- [x] Add Gulp workflow
- [x] integration SCSS (looking at Sussy_)
- [ ] Create Custom Widgets for Social Media
- [ ] Integrate `rdm.php` file to hack the Dashboard
	- [ ] Update `rdm.php` for Wordpress 4.0+ support
- [ ] Include theme options panel
- [ ] Add RDM Shortcode plugin
- [ ] Add CPT plugin

---

#### Plugins to use:

__Theme Development__

* [ACF](http://www.advancedcustomfields.com/)
* [RIU Responsive Images](http://wordpress.org/plugins/riu-responsive-image-uploader/screenshots/)

__Dashboard Hacking__

* [Enable Media Replacement](http://wordpress.org/plugins/enable-media-replace/)
* [Members](https://wordpress.org/plugins/members/)
* [Adminimize](https://wordpress.org/plugins/adminimize/)

__Maintenance, Security & Support__

* [BackupBuddy PREMIUM](http://ithemes.com/purchase/backupbuddy/)
* [iThemes Security](http://ithemes.com/security/)

__Client Usability (post deploy)__

* [Wordpress SEO](http://wordpress.org/plugins/wordpress-seo/) _(also for breadcrumbs)_
* [W3 Total Cache](http://wordpress.org/plugins/w3-total-cache/)

__Notable Mentions__

* [Custom Post Type UI](http://wordpress.org/plugins/custom-post-type-ui/)
* [Client Proof Visual Editor](http://wordpress.org/plugins/client-proof-visual-editor/)
* [Redirection](http://wordpress.org/plugins/redirection/)
* [WooCommerce - Ecom](http://www.woothemes.com/woocommerce/)
* [Exchange - Ecom](http://ithemes.com/exchange/)

