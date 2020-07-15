# UniBuild
Command based scriptable build pipeline for Unity 3D

## How To Install

### Unity Package Installation

Add to your project manifiest by path [%UnityProject%]/Packages/manifiest.json these lines:

```json
{
  "scopedRegistries": [
    {
      "name": "Unity",
      "url": "https://packages.unity.com",
      "scopes": [
        "com.unity"
      ]
    },
    {
      "name": "UniGame",
      "url": "http://packages.unigame.pro:4873/",
      "scopes": [
        "com.unigame"
      ]
    }
  ],
}
```
Open window Package Manager in Unity and install UniBuild 

![](https://i.gyazo.com/724a7a8c10ad8876d1bdd99a4ab7c13f.png)

### Configurations SO

![](https://i.gyazo.com/dbd9eba7427a8f85f2d63d8f0b057f7b.png)

### Menu Items

All Build menu items auto-generated by your build configurations

![](https://i.gyazo.com/042b84f72352c9282b2b244f8c0d7dc5.png)

![](https://i.gyazo.com/22e7c699847e046192b8c12225c046f3.png)

Auto generated content stored in: "Assets\UniGame.Generated\UniBuild\Editor"

![](https://i.gyazo.com/b6e7796ce761e7d93677a3ec7d084904.png)


### Unity Cloud Build Methods

All Cloud methods auto-generated by your build configurations files

![](https://i.gyazo.com/45904cff034647c439c4d1acf76750b4.png)

![](https://i.gyazo.com/515c525d3722fcc11d5224424fecc8bb.png)

![](https://i.gyazo.com/33f0a9d1a11a024a3d60c7769ff0f6bf.png)


