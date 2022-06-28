#### Create different sourcecode
Core code:
```
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'), 'proguard-rules.pro'
        }

        include {
        }

        exclude {
        }
    }
```
You can custom your code under the `include/java` folder.

#### Select sourcecode when coding
You should select the build variants(include, exclude) from Android Studio to ensure your code works correctly.
> The variant selection is normally in the bottom-left side of Android Studio named `Build Variants`.
