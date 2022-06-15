# conf22_OBS1493C
Default inputs.conf for windows and linux TAs based on the details discussed in the conf22 talk: OBS1493C Out With the Old; In With the New! Migrating Your Monitoring From Legacy Windows and *Nix Splunk Apps to ITSI and IT Essentials Work

Update: June 15, 2021
Unfortunately some of the dashboards that were to have been updated to XML support as referenced in the talk didn't make it into the Splunk App for Content Packs 1.6 release. 

This impacts the following three mentioned dashboards inside the Content Pack for Windows Dashboards and Reports
1. Application Crashes - Windows
2. Application Installs - Windows
3. Event Monitoring - Windows

We have been able to get and provide here the updated dashboard for the following:
1. Application Installs - Windows

This has been provided in the proper folder layout, inside the app local directory which is where this modified dashboard should go. Please feel free to include it in your installation which will allow this dashboard to properly populate off of XML formatted data (along with continuing to work with Classic Event format).

We have not been able to get the following dashboards updated yet, but when we are able to get a fix for these it will get posted here:
1. Application Crashes - Windows
2. Event Monitoring - Windows

We will also eventually have these changes published into the content pack itself.
