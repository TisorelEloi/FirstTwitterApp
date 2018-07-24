1
# Project 3 - *Name of App Here*
2
​
3
**Name of your app** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://developer.twitter.com/en/docs/api-reference-index).
4
​
5
Time spent: **X** hours spent in total
6
​
7
## User Stories
8
​
9
The following **required** functionality is completed:
10
​
11
* [X ]  User can **sign in to Twitter** using OAuth login
12
* [X ]  User can **view tweets from their home timeline**
13
  * [ X] User is displayed the username, name, and body for each tweet
14
  * [ ] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
15
  * [ ] User can view more tweets as they scroll with [infinite pagination](http://guides.codepath.com/android/Endless-Scrolling-with-AdapterViews-and-RecyclerView). Number of tweets is unlimited.
16
    However there are [Twitter Api Rate Limits](https://developer.twitter.com/en/docs/basics/rate-limiting) in place.
17
* [ ] User can **compose and post a new tweet**
18
  * [ ] User can click a “Compose” icon in the Action Bar on the top right
19
  * [ ] User can then enter a new tweet and post this to twitter
20
  * [ ] User is taken back to home timeline with **new tweet visible** in timeline
21
​
22
The following **optional** features are implemented:
23
​
24
* [ ] User can **see a counter with total number of characters left for tweet** on compose tweet page
25
* [ ] User can **click a link within a tweet body** on tweet details view. The click will launch the web browser with relevant page opened.
26
* [ ] User can **pull down to refresh tweets timeline**
27
* [ ] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
28
* [ ] User can tap a tweet to **open a detailed tweet view**
29
* [ ] User can **select "reply" from detail view to respond to a tweet**
30
​
31
The following **bonus** features are implemented:
32
​
33
* [ ] User can see embedded image media within the tweet detail view
34
* [ ] User can watch embedded video within the tweet
35
* [ ] Compose tweet functionality is build using modal overlay
36
* [ ] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.com/android/Using-Parceler).
37
* [ ] [Leverage RecyclerView](http://guides.codepath.com/android/Using-the-RecyclerView) as a replacement for the ListView and ArrayAdapter for all lists of tweets.
38
* [ ] Move the "Compose" action to a [FloatingActionButton](https://github.com/codepath/android_guides/wiki/Floating-Action-Buttons) instead of on the AppBar.
39
* [ ] On the Twitter timeline, leverage the [CoordinatorLayout](http://guides.codepath.com/android/Handling-Scrolls-with-CoordinatorLayout#responding-to-scroll-events) to apply scrolling behavior that [hides / shows the toolbar](http://guides.codepath.com/android/Using-the-App-ToolBar#reacting-to-scroll).
40
* [ ] Replace all icon drawables and other static image assets with [vector drawables](http://guides.codepath.com/android/Drawables#vector-drawables) where appropriate.
41
* [ ] Leverages the [data binding support module](http://guides.codepath.com/android/Applying-Data-Binding-for-Views) to bind data into layout templates.
42
* [ ] Replace Picasso with [Glide](http://inthecheesefactory.com/blog/get-to-know-glide-recommended-by-google/en) for more efficient image rendering.
43
* [ ] Enable your app to [receive implicit intents](http://guides.codepath.com/android/Using-Intents-to-Create-Flows#receiving-implicit-intents) from other apps.  When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet.
44
* [ ] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft.  The draft can be resumed from the compose view.
45
​
46
The following **additional** features are implemented:
47
​
48
* [ ] List anything else that you can get done to improve the app functionality!
49
​
