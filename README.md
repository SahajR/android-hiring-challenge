# Android hiring challenge

There are three parts to this challenge.

You are ideally required to complete all of them. However, you can complete any *two* of them if you can write up a solution/way to solve/what you've tried for the third one. The first challenge, however, is compulsory.

**DO NOT use any third-party libraries in the solution project. Only android components and libraries are allowed**

Download the challenge apk from [here](https://github.com/SahajR/android-hiring-challenge/releases/tag/v1.0.0) or use [this direct link](https://github.com/SahajR/android-hiring-challenge/releases/download/v1.0.0/challenge_v1.apk). 

## Common UI elements of android
<img src="/assets/ui_elements.png" width=200 />

- Setup the navigation of the app as a three fragment bottom app bar UI
- Create an edit text that only accepts decimal input
  * It has an editable unit dropdown
  * It lets other UI elements know when the value has changed (**BONUS**: Throttle the input so that the change is propagated only when the value has changed for a significant amount of time)
  * A text view shows the value of the input in grams. Make sure the conversion happens when the unit is set to `Kg`
  * A simple pie chart that shows the total vs supplied amount ratios
  * Both the text view and pie chart are reactive to the changes in the weight value

## Custom views
<img src="/assets/custom_views.png" width=200 />

- Create a custom view that shows ranges when a list of integers (sorted-ascending, between 0 and 100) is given
- <img src="/assets/text.png" width=200 /> This particular text is applied on a `single` text view. Recreate this text view. Notice the color changes within spans.

## Lists and sync app state
<img src="/assets/list_and_sync.png" width=200 />

- The data on the first challenge should be reflected in this screen.
- Add a list that has a `timeline` rail going on the left edge of the list items

## Submitting

Mail the following to [hello@sahajr.com](mailto:hello@sahajr.com?subject=[Hiring%20Challenge]%20Your%20name):
- zipped project (make sure to delete the build directory) or a link to a `fork` of this repository with your app implemented in the [solution folder](/solution)
- APK of the app
- Explanation of how you arrived at the correct tools / android components to develop the solutions
