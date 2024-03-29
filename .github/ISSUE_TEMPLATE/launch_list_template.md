---
name: Launch List
about: Create a launch list issue.
title: 'Launch List'
labels: ''
assignees: ''
---

# Launch List #

## General Setup ##
- [ ] Spam Protection
- [ ] Favicon Generated (including Retina Display)
- [ ] Baseline Performance Reports Generated and Stored on Nest
- [ ] robots.txt File Created
- [ ] meta noindex on All Pages to Be Excluded from Bots
- [ ] Email Delivery Service Setup (Amazon SES/SendGrid/Mandrill/MailGun)
- [ ] Email Marketing System Synced w/ Site (MailChimp/other)

## Front End ##
- [ ] SVG Logos Used Where Possible
- [ ] Print Stylesheet Set and Tested
- [ ] 403 Page Matches Design of Site
- [ ] 404 Page Matches Design of Site
- [ ] Site Offline Page Matches Design of Site
- [ ] Database Error Page Matches Design of Site
- [ ] Site Generated Emails Match Design of Site
- [ ] Review site in Dark Mode (including Samsung Browser)
- [ ] Styleguide Created (excluded in robots.txt)
- [ ] Robots meta tag added (max-snippet:-1, max-image-preview:large, max-video-preview:-1)
- [ ] Add `theme-color` meta tag to fit the site design

## Analytics/Tracking ##
- [ ] Create Google Analytics Account
- [ ] Create GTM Account
- [ ] Track Pageviews
- [ ] Track Scroll Depth
- [ ] Track Video Interactions
- [ ] Track External Links
- [ ] Track File Downloads
- [ ] Track Form Submissions
- [ ] Configure Custom Event Trigger

## Performance ##
- [ ] js/css Optimized and Aggregated
- [ ] CDN Setup (CloudFlare)

### Drupal ###
- [ ] Views Caching Enabled on All Frontend Views
- [ ] Block Visibility Set
- [ ] Modules Cleaned (remove disabled/unneccessary)
- [ ] Development Modules Disabled
- [ ] Logging and Statistics Disabled

### Symfony ###
- [ ] Configure Your Profiler to Use Database
- [ ] Customize Secret Key
- [ ] Configure Query and Metadata Cache
- [ ] Enable HttpCache

### Laravel ###
- [ ] Schedule the necessary application tasks
- [ ] `APP_ENV` in `.env` is set to `production`
- [ ] Cache driver is set correctly
- [ ] Mail driver is set correctly
- [ ] Enable OPCache
- [ ] Ensure PHP Maximum Upload Size is set appropriately to the application needs

## E-Commerce ##
- [ ] SSL Purchased and Configured
- [ ] Google Analytics Properties are ALL E-Commerce Enabled
- [ ] Google Analytics Checkout Goal and Funnel Setup
- [ ] Google Analytics Commerce Flatline Alert Set
- [ ] Payment Gateway is in Live Mode
- [ ] Store Closed Page Matches Design of Site
- [ ] Order Receipt Matches Design of Site
- [ ] Test order placed
- [ ] Transfer Store Ownership to the Customer (if applicable)

## Quality Assurance ##
- [ ] Client User Roles Tested
- [ ] Developer QA
- [ ] Design QA
- [ ] Functional QA
- [ ] Project Management QA

## Accessibility ##
- [ ] There are no generic "read more" links with no further information for screen readers.
- [ ] Images have "alt" tags to prevent screen readers from reading file names.
- [ ] All form inputs have labels. (Placeholders do not suffice.)
- [ ] Ensure the focus outline is not removed for keyboard accessibility.
- [ ] Navigation with hover states and tab order are accessible to keyboard users.
- [ ] Closed Captions on Video

## Pre-Launch ##
- [ ] Setup Redirects
- [ ] Test/Demo Data Removed (Lorem ipsum...)
- [ ] Development Site Auth Directives Removed
- [ ] Google Analytics Site Search Enabled w/ Query String Variable
- [ ] Google Analytics Goals Setup
- [ ] Google Analytics Events Setup
- [ ] Google Analytics URL Builder Query String on Emails
- [ ] Get screen snapshots of key areas of the site at different device sizes
- [ ] Ensure fonts are in production mode
- [ ] DNS RackSpace/CloudFlare
- [ ] Ensure the platform -e flag is set on each build hook
- [ ] Ensure all Google API keys are site restricted

### Wordpress Pre-Launch ###
- [ ] Search Engine Visibility unchecked at Settings > Reading
- [ ] Check wp-config.php information
- [ ] Check Database GUIDs and URLs
- [ ] Using `composer` workflow (package/plugin installs)
- [ ] `.gitignore` unpaid Plugins (automatically installed via Composer)
- [ ] Set up GitHub Actions for WP Engine Deployments

### Wordpress Post Launch ###
- [ ] Change home and site URL in database
- [ ] Set primary domain in WPE
- [ ] Setup domain redirect
- [ ] Clear cache in WPE

## Post Launch ##
- [ ] Confirm SSL Works and Redirects non-SSL
- [ ] Confirm www/non-www Redirects Works
- [ ] Google Analytics Annotation Added for Launch Date
- [ ] Google Analytics Real-Time Verification
- [ ] Google Analytics Traffic Flatline Alert Set
- [ ] XML sitemap Generated and Submitted to Google and Bing
- [ ] Link Checker
- [ ] Site Notifications Going to Correct Accounts
- [ ] Tag the Release revision in GitHub
- [ ] Google Search Console (Webmaster Tools) Account
- [ ] Purchase and configure license key for CMS (depending on framework)

## Monitoring ##
- [ ] Uptime Robot
- [ ] Trustwave
- [ ] Add Platform.sh slack health notification
- [ ] Add Platform.sh activity script for push events

## Final Steps ##
- [ ] Update GitHub Repo with Topics
- [ ] Update `composer.json` with [Authors](https://github.com/grayloon/greet-on-repeat-website/blob/main/composer.json#L7)
- [ ] Finalize README.md
- [ ] Add Status Badges to README.md
- [ ] Update GitHub Wiki (if applicable)
- [ ] Pop Champagne in Kitchen and Post to Social Media
- [ ] Test social sharing preview on Facebook, Twitter, etc..

