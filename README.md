A manifesto for developers that want to make the App Store a better (and more ethical) place
===================

I'm tired of App Store getting worse and developers using "gray-zone" practices or apps developed with no attention to details.

This is an effort to gather developers together and fight for a better App Store - for users and developers. Pull Requests are welcome.

1. Don't prompt users to review your app. Or at least present a "No, thanks" option and respect it forever, not only the current version. And present it on a proper moment, not when your user opened your app to do something. More on http://unretrofied.com/blog/2013/12/app-store-review-prompts.
2. Don't A/B test In-App Purchase prices. Your users aren't dumb.
3. Respect limited advertising tracking. From [documentation](https://developer.apple.com/library/ios/documentation/AdSupport/Reference/ASIdentifierManager_Ref/ASIdentifierManager.html):
   > If the user has limited ad tracking, use the advertising identifier only for the following purposes: frequency capping, conversion events, estimating the number of unique users, security and fraud detection, and debugging.

4. Don't send push notifications only to "engage" your users. They were created so the user can be notified when something that she cares happened. Not to remember to open your app. Usually, the user must opt-in in recurring notifications (e.g. users don't want to be notified when **any** sports game startd - only the ones from their favorite teams).
5. Create great screenshots. Don't show a low battery indicator, carrier name or "iPod". Use "9:41 AM" as the time in the status bar.
6. Read [iOS Human Interface Guidelines](https://developer.apple.com/library/ios/documentation/userexperience/conceptual/mobilehig/) and apply it. A modal controller shouldn't have a "Back" button, but a "Done" or "Cancel" one. Any action on a tab shouldn't change the app to another tab.
7. Don't review your app. You aren't in position to make a neutral review. Any employee from a company involved in an app shouldn't review it either. It's even worse if the company incentives employees to do review the app.
8. Don't abuse background fetching. For example, if your content only is updated when the user is logged and she currently is not, just disable background fetching.
9. It's "iOS", not "IOS" or "ios".
10. Make sure that the "bundle display name" (the text that iOS uses to label your app on SpringBoard) is short enough and "..." doesn't show up.

