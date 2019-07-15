# 📬 SOA Exam Updates

![soa registration page](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/soa-exam-registration.png)

## Get Distill

[Distill Web Monitor](https://distill.io/) is a cloud based application for monitoring website changes. The steps below are with the [Chrome extension](https://chrome.google.com/webstore/detail/distill-web-monitor/inlikjemeeknofckkjolnjbpehgadgge). But, a [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/distill-web-monitor-ff/) is also available.

## Add to Watchlist

1. Go to the [SOA exam registration](https://www.soa.org/education/exam-req/registration/edu-registration/) page:
`https://www.soa.org/education/exam-req/registration/edu-registration/`.

2. Click the Distill extension icon on the top right, then choose`Add Monitor` > `Select parts of page`. Hover over the exam selector and click. The *XPath* expression should be `//select[@id='ddlExam']` with the exam options text appearing on the right.

![select-element](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/select-element.png)

3. Click `Save selections` and set the monitor properties.
  * **Name**: Give the monitor a name (e.g. *SOA registration updates*)
  * **Schedule checks**: Set the interval to `1 day`
  * **Actions**: Add an email action to receive notifications when the registration status (open/closed) changes
  * **Conditions**: Leave blank or add a condition to filter on specific exams
  * Click the `Save` button

4. On the Watchlist page, set the `device to run on` to `webapp`. The monitor should be `ON` with a `blue cloud` icon next to it. This way, the monitor will run even when you are offline. 

![distill watchlist](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/distill-watchlist.png)

## Profit!

Now you will receive emails when your exam opens for registration.

![email alert](https://raw.githubusercontent.com/Infinite-Actuary/exam-registration-updates/master/img/email-alert.png)
