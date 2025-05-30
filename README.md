# Unity-Scene-Reference
Adds a scene reference to the Unity inspector.

## How to install
This package can be installed through the Unity `Package Manager` with Unity version 2019.3 or greater.

Open up the package manager `Window/Package Manager` and click on `Add package from git URL...`.

Paste in this repository's url.

`https://github.com/Jason-Skillman/Unity-Scene-Reference.git`

Click `Add` and the package will be installed in your project.

---
**NOTE:** For Unity version 2019.2 or lower

If you are using Unity 2019.2 or lower than you will not be able to install the package with the above method. Here are a few other ways to install the package.
1. You can clone this git repository into your project's `Packages` folder.
1. Another alternative would be to download this package from GitHub as a zip file. Unzip and in the `Package Manager` click on `Add package from disk...` and select the package's root folder.

---

### Git submodule
Alternatively you can also install this package as a git submodule.

```console
$ git submodule add https://github.com/Jason-Skillman/Unity-Scene-Reference.git Packages/Scene-Reference
```

## Scene Reference usage
```
[SerializeField]
private SceneReference sceneRef; 
```

## Sources
- https://github.com/JohannesMP/unity-scene-reference
- https://github.com/Tymski/SceneReference
