# eppz!

**Unity everydayers** master project.

## Install

Add this repository as **a submodule to your project** repository into `Assets/Plugins/eppz!` (track `master` branch, then update submodules recursive). 

```
git submodule add -f https://github.com/eppz/Unity.Library.eppz Assets/Plugins/eppz!
git config -f .gitmodules submodule.'Assets/Plugins/eppz!'.branch master
git submodule update --init --recursive --remote Assets/Plugins/eppz!
```

> You can opt-out submodules best by fork this repository, then simply remove unnecessary submodules (so you'll still have versioning and uplink maintained).

## Modules

* [Easing](https://github.com/eppz/Unity.Library.eppz.Easing)

	+ Normalized easing functions. See standalone project repository [Unity.Library.eppz_easing](https://github.com/eppz/Unity.Library.eppz_easing) for details.

* [Extensions](https://github.com/eppz/Unity.Library.eppz.Extensions)

	+ String extensions for the everyday. 

* [Meshes](https://github.com/eppz/Unity.Library.eppz.Meshes)

	+ Procedural runtime ring and circle mesh creator classes for Unity.	

* [Utils](https://github.com/eppz/Unity.Library.eppz.Utils)

	+ 🛠️ Collection of Unity helper tools. Mostly small, single filed utility classes (they grouped here as they don't earned their own repositories yet).

## License

> Licensed under the [MIT license](http://en.wikipedia.org/wiki/MIT_License).
