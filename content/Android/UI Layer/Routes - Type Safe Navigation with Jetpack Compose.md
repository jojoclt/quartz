---
draft: "true"
---
Normally when we want to define a navigation destination with Jetpack Compose, we need to do it using 
```kotlin
composable("Profile") {
	ProfileScreen()
}
```

Which is very prone to error because the routes is hardcoded to the 