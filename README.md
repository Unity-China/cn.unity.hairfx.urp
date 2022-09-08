# cn.unity.hairfx.urp
The Unity HairFX Custom Hair ShaderGraph Shader for Universal Render Pipeline (URP)

## Requirements

- Unity 2021.2.13f1 +
- Universal Render Pipeline 12.1.4 +


## Features

This Package included a Custom Hair ShaderGraph Shader supports for Universal Render Pipeline (URP), and support for cross platform from desktop computer, consoles to mobile devices.


## Note

- This Package included a Custom Hair ShaderGraph Shader for URP only.
- This Package required a dependency: [HairFX Core](https://github.com/Unity-China/cn.unity.hairfx.core) package
- URP Defender Character Demo Project [here](https://github.com/UnityTechnologies/URP-Defender-Character-Demo)

## Usage

Declare the package and its dependencies as git dependencies in `Packages/manifest.json`:

```
"dependencies": {
    "cn.unity.hairfx.core": "https://github.com/Unity-China/cn.unity.hairfx.core.git",
    "cn.unity.hairfx.urp": "https://github.com/Unity-China/cn.unity.hairfx.urp.git",
    ...
}
```

## Tips
If you build this hair system to mobile platform, please try to limit the total hair strand count less then 10 thousand in the viewing screen to maintain good frame rate. The performance of FPS is also depend on your device hardware.


## Known Issues
Currently not supports Huawei mobile phones due to some device does not support StructuredBuffer for vertex program in shader

## Related links
[AMD TressFX](https://github.com/GPUOpen-Effects/TressFX)
