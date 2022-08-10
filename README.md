Unscramble App
=======================

Introduction
------------
You have learned in the previous codelabs, how to use a [ViewModel](https://developer.android.com/reference/android/arch/lifecycle/ViewModel) to store the app data. ViewModel allows the app's data to survive configuration changes. In this codelab, you'll learn how to integrate [LiveData](https://developer.android.com/reference/android/arch/lifecycle/LiveData.html) with the data in the ViewModel.

The LiveData class is also part of the [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) and is a data holder class that can be observed.

Prerequisites
-------------
- How to download source code from GitHub and open it in Android studio.
- How to create and run a basic Android app in Kotlin, using activities and fragments.
- How the activity and fragment life cycles work.
- How to retain UI data through device-configuration changes using a [ViewModel](https://developer.android.com/reference/android/arch/lifecycle/ViewModel).
- How to write lambda expressions.

What you'll learn
-----------------
- How to use [LiveData](https://developer.android.com/reference/androidx/lifecycle/LiveData) and [MutableLiveData](https://developer.android.com/reference/android/arch/lifecycle/MutableLiveData) in your app.
- How to encapsulate the data stored in a ViewModel with LiveData.
- How to add observer methods to observe changes in the LiveData.
- How to write binding expressions in a layout file.

What you'll build
-----------------
- Use LiveData for the app's data (word, word count and the score) in the Unscramble app.
- Add observer methods that get notified when the data changes, update the scrambled word text view automatically.
- Write binding expressions in the layout file, which are triggered when the underlying LiveData is changed. The score, word count and the scrambled word text views are updated automatically.

What you need
-------------
- A computer with Android Studio installed.
- Solution code from the previous codelab (Unscramble app with ViewModel).
