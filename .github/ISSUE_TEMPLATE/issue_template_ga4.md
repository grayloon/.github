---
name: GA4 Migration List
about: Create an issue on an actionable task.
title: 'GRA-P22 GA4 Migration'
labels: ''
assignees: ''
---

<!-- NOTE: C+P Job number is required in the title. -->

## Record GA4 Start Date: [MM-DD-YYYY]
Some properties will already be gathering data on a GA4 stream. We need to record that date to know exactly how much historical data we'll have to work with once Universal Analytics data is deleted.

## Migration Steps

- [ ] Verify all enhanced measurements are turned on (except Form Interactions) [REF](https://docs.google.com/document/d/1H94GfLojHRfB6oZ7-ymb7N5JX1IF_VvLp4ADHRUnq8w/edit#bookmark=id.x151lqfsupas)

### User and Event Data Retention
- [ ] Update data retention period from 2 months to 14 months. [REF](https://docs.google.com/document/d/1H94GfLojHRfB6oZ7-ymb7N5JX1IF_VvLp4ADHRUnq8w/edit#bookmark=id.hhb1f7dwd2c3)

### Setup Assistant 
Follow along with the GA4 setup assistant to complete the following steps. [REF](https://docs.google.com/document/d/1H94GfLojHRfB6oZ7-ymb7N5JX1IF_VvLp4ADHRUnq8w/edit#bookmark=id.5jsbpato4aut)

- [ ] Data Flowing
- [ ] Turn on Google Signals
- [ ] Migrate/QA Goals to Conversion Events
- [ ] Link Google Ads
- [ ] Link Google Search Console
- [ ] Verify User Import
- [ ] Migrate existing audiences if applicable
- [ ] All Items Marked as Complete

### Disable Auto Migration

- [ ] Uncheck “Automatically set up a basic Google Analytics 4 property” for all Universal Analytics properties.

### Alerts

- [ ] Enable Necessary Anomaly Alerts [REF](https://docs.google.com/document/d/1H94GfLojHRfB6oZ7-ymb7N5JX1IF_VvLp4ADHRUnq8w/edit#bookmark=id.o0jmpuxf3dz3)

### Google Tag Manager

- [ ] Update Google Tag Manager so that the primary GA4 tag uses the "Initialization - All Pages" trigger.

### Remove Defunct Properties
There are many properties currently not in use. This is our chance to clean them up. Or at least, turn off auto migration if we have concerns removing them. However, if no data has been collected in the last year, it should generally be safe to delete those.

- [ ] Clean Up Unused Properties (turn off auto migration)

## Export Data
TBD

## Completion Date: [MM-DD-YYYY]

## Cleanup

- [ ] After July 1, 2023, remove Universal Analytic Scripts from Sites/GTM
