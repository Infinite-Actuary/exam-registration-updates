# SOA Exam Updates

![soa registration page](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/soa-exam-registration.png)

## Get Distill

[Distill Web Monitor](https://distill.io/) is a cloud based application for monitoring website changes. First, get the extension on [Firefox](https://addons.mozilla.org/en-US/firefox/addon/distill-web-monitor-ff/) or [Chrome](https://chrome.google.com/webstore/detail/distill-web-monitor/inlikjemeeknofckkjolnjbpehgadgge).

## Add to Watchlist

1. Go to the [SOA exam registration](https://www.soa.org/education/exam-req/registration/edu-registration/) page:
`https://www.soa.org/education/exam-req/registration/edu-registration/`.

2. Click the extension icon on the top right, then choose`Add Monitor` > `Select parts of page`. Hover over the exam selector and click. The XPath expression should be `//select[@id='ddlExam']` and the exam options text should appear on the right.

![select-element](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/select-element.png)

3. Click `Save selections`.
  * **Name**: Give the monitor a name (e.g. *SOA registration updates*)
  * **Schedule checks**: Set the interval to `1 day`. 
  * **Actions**: Add an email action to receive notifications when the registration status (open/closed) changes
  * **Conditions**: Leave blank or add a condition to filter on specific exams
  * Click the `Save` button

4. Now on the Watchlist page, make sure the device to run on is set to `webapp`. This way, the monitor will run even when you are offline. Make sure you see the `blue cloud` on the right and that the monitor is `ON`.

![distill watchlist](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/distill-watchlist.png)

## Profit

You should now receive emails when your exam registration status changes!

![email alert](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/email-alert.png)
