# ml_kit_graphics_overlay
A library made to make graphics overlay on MLKit easier

In order to use this library, first, go to settings.gradle of your project
Add the following maven url as

```
dependencyResolutionManagement {
    ...
    repositories {
        ...
        maven {
          url 'https://jitpack.io'
        }
    }
}
```

After that go to build.gradle (Module level) and add the following dependency

```
dependencies {
    ...
    implementation 'com.github.suprimpoudel:ml_kit_graphics_overlay:1.0.0'
}
```
