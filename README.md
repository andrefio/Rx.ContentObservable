# Rx.ContentObservable

Content bindings from RxAndroid [v0.25.0](https://github.com/ReactiveX/RxAndroid/tree/v0.25.0/rxandroid/src/main/java/rx/android/content).

## Background

The RxAndroid creators decided to remove APIs deemed "not absolutely fundamental to all apps" beginning in the library's v1.0.0 release. They wanted the demoted APIs and bindings to move into their own projects and be maintained separately.

This project is meant to preserve the legacy, and yet, still useful content bindings.

## Binaries

[![Release](https://jitpack.io/v/io.andref/Rx.ContentObservable.svg)](https://jitpack.io/#io.andref/Rx.ContentObservable)

Add the JitPack repository to your root build.gradle at the end of repositories:

```groovy
    allprojects {
        repositories {
            ...
            maven { url "https://jitpack.io" }
        }
   }
```

And then add this library to your project:

```groovy
   dependencies {
        compile 'io.andref:Rx.ContentObservable:1.0.0'
   }
```


## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.