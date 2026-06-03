# SDK 库文件 / SDK Libraries

本仓库不再托管预编译库文件（已从 Git LFS 移除以节省存储配额）。

This repository no longer hosts prebuilt library files (removed from Git LFS to save storage quota).

## 获取库文件 / Obtaining Libraries

请从珞石官方渠道获取与 SDK 版本匹配的预编译库，并按以下目录结构放置：

Obtain prebuilt libraries matching the SDK version from ROKAE official channels and place them in the following directory structure:

### Linux

```
lib/Linux/cpp/x86_64/
  libxCoreSDK.a
  libxCoreSDK.so.<version>
  libxCoreSDK.nomodel.so.<version>   # when XCORE_USE_XMATE_MODEL=OFF
  libxMateModel.a                    # when XCORE_USE_XMATE_MODEL=ON

lib/Linux/cpp/aarch64/
  libxCoreSDK.a
  libxCoreSDK.so.<version>
```

### Windows

```
lib/Windows/cpp/Debug/<32bit|64bit>/
  xCoreSDK.dll
  xCoreSDK.lib
  xCoreSDK_static.lib
  xCoreSDK.pdb
  xMateModeld.lib                    # Debug, 64bit only

lib/Windows/cpp/Release/<32bit|64bit>/
  xCoreSDK.dll
  xCoreSDK.lib
  xCoreSDK_static.lib
  xMateModel.lib                     # Release, 64bit only
```

如有疑问请联系珞石客户支持。

For questions, please contact ROKAE customer support.
