## Quick Package Install

#### Using UnityPackageManager (for Unity 2019.3 or later)
Open the package manager window (menu: Window > Package Manager)<br/>
Select "Add package from git URL...", fill in the pop-up with the following link:<br/>
https://github.com/SoprachevAK/AppleColorPaletteMaterialURP.git<br/>

#### Using UnityPackageManager (for Unity 2019.1 or later)

Find the manifest.json file in the Packages folder of your project and edit it to look like this:
```js
{
  "dependencies": {
    "com.soprachevak.apple-color-palette-material-urp": "https://github.com/SoprachevAK/AppleColorPaletteMaterialURP.git",
    ...
  },
}
```

<!-- DOC-START -->
<!-- 
Changes between 'DOC START' and 'DOC END' will not be lost on package update 
-->

## Description
Add colors material from apple guidelines


## Usage
* From material: Contains Opaque and Transparent material with URP shader and enabled GPU Instancing   

<!-- DOC-END -->

## Author

**Soprachev Andrei**


## Show your support

Give a ⭐️ if this project helped you!