# eppz! [![Build Status](https://travis-ci.org/eppz/Unity.Test.eppz.png?branch=master)](https://travis-ci.org/eppz/Unity.Test.eppz)

**Unity everydayers** master project.

## Install as submodule

Add this repository as **a submodule to your Unity project** repository into **`Assets/Plugins/eppz!`**. Hook up directly this repository (explicitly tracking `master` branch), then update / initialize submodules (recursive).

```
git submodule add -b master -f https://github.com/eppz/Unity.Library.eppz Assets/Plugins/eppz!
git submodule update --init --recursive --remote Assets/Plugins/eppz!
```

> 💡 You can opt-out submodules best by fork this repository, then simply remove unnecessary submodules (so you'll still have versioning and uplink maintained to the rest).

## Install as direct download	

Alternatively, you can **directly download** the [**`Unity.Library.eppz-master.zip`**](https://github.com/eppz/Unity.Library.eppz/archive/master.zip), then extract it to **`Assets/Plugins/eppz!`** in your Unity project folder.

> 💡 Having it stored in `Assets/Plugins` folder means that the library code won't get recompiled every time Unity compiles your project code.

## Modules

* [Cloud](https://github.com/eppz/Unity.Library.eppz.Cloud)

	+  iCloud Key-value store native iOS plugin for Unity. With callbacks on changes per value.

* [DeepLink](https://github.com/eppz/Unity.Library.eppz.DeepLink)

	+  Deep linking native iOS plugin for Unity. With deep link callbacks on app launch as well.

* [Easing](https://github.com/eppz/Unity.Library.eppz.Easing)

	+ Normalized easing functions. See standalone project repository [Unity.Library.eppz_easing](https://github.com/eppz/Unity.Library.eppz_easing) for details.

* [Extensions](https://github.com/eppz/Unity.Library.eppz.Extensions)

	+ String extensions for the everyday.

* [Geometry](https://github.com/eppz/Unity.Library.eppz.Geometry)

	+ 📐 2D Geometry for Unity.

* [Lines](https://github.com/eppz/Unity.Library.eppz.Lines)

	+ Lightweight OpenGL line rendering for Unity. Like `Debug.DrawLine` in Game view.

* [Meshes](https://github.com/eppz/Unity.Library.eppz.Meshes)

	+ Procedural runtime ring and circle mesh creator classes for Unity.

* [Networking](https://github.com/eppz/Unity.Library.eppz.Networking)

	+ Unity networking for the everyday.

* [Persistence](https://github.com/eppz/Unity.Library.eppz.Persistence)

	+ 📦 Object serialization (Binary, JSON, Gzip) wrapped up for the everyday.

* [Rate](https://github.com/eppz/Unity.Library.eppz.Rate)

	+ App Store rate mechanisms native iOS plugin for Unity.

* [Utils](https://github.com/eppz/Unity.Library.eppz.Utils)

	+ 🛠️ Collection of Unity helper tools. Mostly small, single filed utility classes (they grouped here as they don't earned their own repositories yet).

## License

> Licensed under the [MIT license](http://en.wikipedia.org/wiki/MIT_License).
