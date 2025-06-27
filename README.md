These are .NET 9 bindings for the newest version of [Lottie Android](https://github.com/airbnb/lottie-android) v6.6.7 (June 2025)

Install `QotoQot.Bindings.Lottie.Android`, from Nuget, add `YourAnimation.json` into `Assets/` in your .NET Android project, and then in your code:


```csharp
using Com.Airbnb.Lottie;
…
var animationView = new LottieAnimationView(Context);
animationView.SetAnimation("YourAnimation.json");
animationView.RepeatCount = -1; // loop
animationView.PlayAnimation();
// some LayoutParams here
AddView(animationView);
```

## Requirements

- .NET 9.0 or later
- Android API 21 (Android 5.0) or later

## Dependencies

This package includes bindings for:
- Lottie Android v6.6.7
- AndroidX AppCompat
- AndroidX Core
- OkIO (transitive dependency)

## Lottie for iOS

Get the sources [from Github](https://github.com/QotoQot/Bindings.Lottie.iOS) or the package [from Nuget](https://www.nuget.org/packages/QotoQot.Bindings.Lottie.iOS).
