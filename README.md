# About

metal-cpp-extensions 是一个搭配 metal-cpp 使用的库。

# 使用方法

```
vcpkg add port metal-cpp-extensions
```

baseline 建议替换为 [hollykbuck/vcpkg_registry](https://github.com/hollykbuck/vcpkg_registry) 最新 commit。

```json
    {
      "kind": "git",
      "repository": "https://github.com/hollykbuck/vcpkg_registry",
      "reference": "main",
      "baseline": "9a433047996b4ae6d92130c08d5e8e2259b3216c",
      "packages": [
        "metal-cpp", "metal-cpp-extensions"
      ]
    }
```

## 联动

[metal-cpp](https://developer.apple.com/metal/cpp/) 官方版本
[hollykbuck/metal-cpp](https://github.com/hollykbuck/metal-cpp) 我打包的版本
[hollykbuck/vcpkg_registry](https://github.com/hollykbuck/vcpkg_registry) vcpkg 个人仓库