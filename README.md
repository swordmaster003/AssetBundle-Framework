# AssetBundle-Framework
AssetBundle Framework ia a complete solution for network game to manage assets.

![image](https://github.com/swordmaster003/AssetBundle-Framework/blob/master/Screenshots/Cover.png)

## Support Unity Versions

5.6.6 or higher

## Download

You can download this asset from Unity Asset Store:

[AssetBundle Framework](https://assetstore.unity.com/packages/tools/gui/https://assetstore.unity.com/packages/tools/utilities/assetbundle-framework-91325)

## Online Documents:

[AssetBundle Framework Manual](https://www.swordmaster.info/unity-asset-documents__trashed/asset-bundle-framework-introduction-document/)

## Key Features

- Three AssetBundle mode would be used in the unity editor:

(1)NoAssetBundleMode: load asset from directory called BuildAssetBundlesPath directly, without ever building an AssetBundle.

(2)AssetBundleDebugMode:you need not to build you own asset server,the directory which AssetBundles are saved will become your asset server's assets folder which simulate the real asset server.

(3)AssetBundleCompleteMode:The complete process pattern for the framework,you have to build your own asset server.

![image](https://github.com/swordmaster003/AssetBundle-Framework/blob/master/Screenshots/1.png)

- Asset Dependency Management including AssetBundle Manifests that keep track of every AssetBundle and all of their dependencies.Assets Dependencies are handled automatically by the AssetBundle Framework .With AssetBundle Manifests it is possible to query all AssetBundles and their dependencies.

- Support the API of loading asset synchronously and the API of loading assets asynchronously.

- AssetBundle Encryption: You can build two types of AssetBundles,the unencrypted AssetBundles or the encrypted AssetBundles.

  ![image](https://github.com/swordmaster003/AssetBundle-Framework/blob/master/Screenshots/3.png)

  The framework provide four encryption algorithm for you,you can select which you prefer's. Building the encrypted AssetBundles can protect your AssetBundle with the encrypt key,and the encrypted AssetBundles are only be decrypted when assets need be loaded into memory.
  
  ![image](https://github.com/swordmaster003/AssetBundle-Framework/blob/master/Screenshots/4.png)

- The AssetBundles' num and the directory structure which stored AssetBundles in persistence path on device wil stay consistent with the   Asset Server's.

- Povide the object pool of Assets which is easy to use,and it will make your game more smoothly .

- Provide the complete source code, convenient debugging and adjustment in your project.
