## HoloLens-AzurePipelineMRTKv2

[![Build Status](https://dev.azure.com/guitarrapc-oss/HoloLens%20App/_apis/build/status/guitarrapc.HoloLens-AzurePipelineMRTKv2?branchName=master)](https://dev.azure.com/guitarrapc-oss/HoloLens%20App/_build/latest?definitionId=3&branchName=master)

Unity Build (IL2CPP)

```
Start-UnityEditor -Project . -Version 2018.3.13f1 -ExecuteMethod Microsoft.MixedReality.Toolkit.Build.Editor.UnityPlayerBuildTools.StartCommandLineBuild -BuildTarget WSAPlayer -Wait -BatchMode
```

MSBuild (IL2CPP C++ build)

```
"C:\Program Files (x86)\Microsoft Visual Studio\2019\Professional\MSBuild\Current\Bin\MSBuild.exe" Builds/WSAPlayer/UnitySample.sln /p:PlatformToolset=v142;Configuration=Release;Platform=x64;AppxBundle=Always;AppxBundlePlatforms=x64
```

appx output at

> Builds\WSAPlayer\AppPackages\UnitySample\UnitySample_1.0.4.0_Test>
