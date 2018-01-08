# AndroidCV — SDK
This is just a mirror of the OpenCV SDK which I use as a git submodule in my projects to forgo the pain of updating manually.

To compile in a given module, just include the following in your ```build.gradle```: 
```
dependencies {
  ...
  compile project(":AndroidCV-SDK")
}
