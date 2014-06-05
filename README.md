# Sennza Maintenance Helper For Mailchimp

Once a month at Sennza we send out maintenance emails to clients in Mailchimp that inform our clients of the core and plugin updates we have completed on their websites as part of their maintenance plan.

Altering the markup that is generated on the WordPress Updates screen was time consuming so we've created this plugin to generate the markup for us so we can paste it straight into MailChimp.

##Installing

1. Down the zip from Github.
2. Upload the zip.
3. Activate the plugin and browse to Settings->Maintenance Helper.
4. For plugin updates from Github we recommend you install the following plugin: https://github.com/afragen/github-updater

##Usage for Maintenance

1. Create a staging site
2. Upgrade core, plugins and themes.
3. Test the major features of the site to ensure that the plugins were update successfully and nothing was broken.
4. If the updates were successful then install and activate this plugin on the live site.
5. Browse to Settings->Maintenance Helper.
6. Copy and paste the HTML into MailChimp.
7. Backup the main site.
8. Upgrade the site.
9. Send the Mailchimp Maintenance to the clients.
10. Rejoice.

##Screenshot

![Screenshot](screenshot.png?raw=true "Screenshot")