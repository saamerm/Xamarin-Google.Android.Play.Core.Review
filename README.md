## Google.Android.Play.Core.Review Library Bindings for Xamarin.Android

The Xamarin bindings library for the Google.Android.Play.Core.Review v2.0 and higher.

This repo contains a NuGet package that allows you to Support **in-app reviews** in your Xamarin Forms Android Apps.

## Screenshots

### In-App Review

## Download
 
## Implementation

```
```
- To support In-App Reviews, you need to use Dependency Injection to call the Review workflow from your Shared Project. Add an interface in the Shared Project and implement that interface in your Android project.
- Although optional, using [James Montemagno's Current Activity Plugin](https://github.com/jamesmontemagno/CurrentActivityPlugin) is recommended to retrieve the Context for the IReview object. Alternatively, the Sample uses a static object to pass the Context to the IAppReview implementation or you can use a singleton.

To make it easier for you, check the Sample project to see examples of implementations for the feature.

## Google Guidelines
- See Android's Official [Play Core In-App-Review docs](https://developer.android.com/guide/playcore/in-app-review) for info on In-App Reviews guidelines. 

## Possible Pitfalls
- You need to have the app submitted to at least an internal test track or internal app sharing to fully test the features. 

- If you test in-app reviews with an app submitted to Internal App Sharing, the **Submit** button for the review will be grayed out. This is also clearly stated in the Google docs. 


