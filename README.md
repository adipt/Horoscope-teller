# Horoscope-teller
Basic web scraping and Regular Expressions to find daily, monthly, weekly, and yearly horoscope from findmyfate.com
This program behave differently in Windows and Linux. It remains untested on mac.

First, after verifying that the DOB provided by user is correct, it predicts the sign. Then, it picks the respective horoscope and displays it.

In Windows, the program simply waits until user asks it to do something else, like refreshing the horoscope, or providing the horoscope for some other DOB, or exiting.

On the other hand, in Linux, the program waits for the user to ask it to exit or change DOB, but does not refresh until new horoscope is available, i.e. until the day changes.
