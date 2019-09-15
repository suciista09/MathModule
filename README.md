# MathModule
learning about multi project in java

## How to use as your module
adding this in setting.gradle
```
sourceControl {
    gitRepository("https://github.com/suciista09/MathModule.git") {
        producesModule("org.suci.module:mathModule")
    }
}
```
then add dependecies n your build.gradle
```
dependencies {
    
    implementation 'org.suci.module:mathModule:1.0.0'
}
```
