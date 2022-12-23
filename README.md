Tempo Android Library releases

### To consume the library 

1. Add below code in setings.gradle file under repositories section  
```
repositories {
      mavenCentral()
  }
```
2. Add the below line in build.gradle file under dependencies. Use the latest release number (0.0.x)
```
dependencies {
      ...
      implementation 'io.github.tempo-platform:tempo-android-sdk:0.0.11'
   }

```
3. This allows you to import the library 
```
   import com.tempoplatform.ads.InterstitialView
```

### To Release a new version - old instructions, pre-death-of-jitpack
1. Checking a new .aar file to the repo 
2. Go to [releases](https://github.com/Tempo-Platform/tempo-android-sdk-release/releases) in Github. 
   Then click on "Draft a new release". Add a new tag 0.0.x (increment the last digit)
3. Go to jitpack.io and paste the url "https://github.com/Tempo-Platform/tempo-android-sdk-release" in search bar. 
   Wait for the built to succeed. Fix errors if any.
4. That is all, you can now use the library with the new tag you created above.


### To consume the library - old instructions, pre-death-of-jitpack

1. Add below code in setings.gradle file under repositories section  
```
repositories {
      maven { url 'https://jitpack.io' }
  }
```
2. Add the below line in build.gradle file under dependencies. Use the latest release number (0.0.x)
```
dependencies {
      ...
      implementation 'com.github.Tempo-Platform:tempo-android-sdk-release:0.0.4'
   }

```
3. This allows you to import the library 
```
   import com.tempoplatform.ads.InterstitialView
```
