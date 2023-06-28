---
name: GA4 Default Setup
about: Create an issue on an actionable task.
title: 'GRA-P22 GA4 Setup'
labels: ''
assignees: ''
---

The following tracking measures are expected to be in place for every site by default. Any tracking outside this scope will need to be discussed on a per site basis and at added cost.

## GA4 Built In Events
- [ ] Page views
- [ ] Scrolls
- [ ] Outbound links
- [ ] Site searches
- [ ] Video engagement
- [ ] File downloads

Note: Do not enable Form Interactions.

## Ecommerce
The following recommended events from Google should be measured on all ecommerce sites:
- [ ] add_payment_info
- [ ] add_shipping_info
- [ ] add_to_cart
- [ ] begin_checkout
- [ ] purchase
- [ ] remove_from_cart
- [ ] view_cart
- [ ] view_item

## Form Submissions
GA4 does have built in form interactions. However, we are not turning this on by default. It should be disabled. All forms should be tracked as a form_submission.

```
Event name: form_submission
Parameter: form_id or form_url (which ever best describes the form when viewing analytics)
```

- [ ] All form submissions tracking

### Klaviyo
Klaviyo forms can not be tracked by normal form submit listeners. 

The recommended method for tracking these forms is outlined here:  
https://www.analyticsmania.com/post/track-klaviyo-forms-with-google-tag-manager

## Newsletter/Email Signups
While all form submissions are being tracked, email marketing submissions should be tracked as its own event.

```
Event name: newsletter_signup
Parameter: [header|footer|other] (if applicable)
```

- [ ] Newsletter signups tracking

_Some clients will consider newsletter signups as a conversion. This should be discussed on a per site basis. Newsletter signups should not be marked as a conversion by default._

## Dealer Locator Usage
If a site has a dealer locator feature, this should be tracked by default. Ideally, we would track usage of the dealer locator and not just landing on the dealer page. However, this may depend on the site.

An example of how I’m tracking dealer usage:
```
Event name: dealers
Event action: search / error
Event label: geolocated (tracking if a user searches by zip or by current location)
```

- [ ] Dealer locator tracking

_Some clients will consider dealer locator usage as a conversion. This should be discussed on a per site basis, and it should not be marked as a conversion by default._

## Nav Usage
Navigation tracking is not expected by default. This should be discussed per site and require added cost.

## Filter Tool Usage
If there is a filtering tool on the site, we should track that usage. 

```
Event name: [name of the tool]
Parameter: [filter value selected]
```

- [ ] Filter tools tracking

## Keeping Track of Custom Events and Conversions
Custom events outside those outlined above should be added to the site's wiki.

Possible example: https://github.com/grayloon/indiana-furniture-website/wiki/Analytics

- [ ] Custom events added to wiki

## Managing Alerts, Anomalies, Etc.
When creating anomaly alerts, they need to go to [analytics@grayloon.com](mailto:analytics@grayloon.com), by default, and any other email addresses that will need that notification. 

When creating alerts in GA4, the signed in account will be assigned the alert and this cannot be changed. It is recommended to sign in to GA4 with [analytics@grayloon.com](mailto:analytics@grayloon.com) first, before setting up these alerts.

- [ ] Alerts enabled for analytics@grayloon.com and any other email addresses as needed per site

## GA4 Setup
- [ ] Web stream shows data flowing (at launch)
- [ ] Link Google Ads
- [ ] Link Google Search Console

## Reference
Reference documentation: https://docs.google.com/document/d/1yY4F_NdYlVWSWXsFsCgehbXxJKZFbuYLq83gsdM72c4
