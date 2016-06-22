This styles the default New Relic partner iframe to look like the example images below

How To Deploy
=============
Navigate to the _live_ appserver binding of the marketing site, and update the `new_relic` directory

```
@hubot site me pantheon.io
Use the debug panel to find the appserver for the live environment
ssh onto it, using the listed ssh command
cd code/sites/default/files/new_relic
git pull origin master
```

Update the partner admin dashboard

[https://partner-admin-console.newrelic.com/accounts/66686/admin_console/partnerships/1184/settings](https://partner-admin-console.newrelic.com/accounts/66686/admin_console/partnerships/1184/settings)

Example Images
==============
![Empty State](https://github.com/kimby77/newrelic-partner-iframe-css/blob/master/example_images/empty_state.png)

`The empty state`

![Populated state](https://github.com/kimby77/newrelic-partner-iframe-css/blob/master/example_images/populated_state.png)

`The "populated" state`
