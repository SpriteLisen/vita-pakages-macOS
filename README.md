## VitaSDK packages macOS Version.

* Use vitasdk default packages, wiliwili [curl](https://github.com/xfangfang/wiliwili/tree/yoga/scripts/psv/curl), [ffmpeg](https://github.com/xfangfang/wiliwili/tree/yoga/scripts/psv/ffmpeg), [mbedtls](https://github.com/xfangfang/wiliwili/tree/yoga/scripts/psv/mbedtls), [mpv_gxm](https://github.com/xfangfang/wiliwili/tree/yoga/scripts/psv/mpv_gxm).

### How to use?

1. Use repo vita-makepkg file replace origin file.


2. Go to target package folder, exec under command.

```bash
bash vita-makepkg -C -f -d
```

3. You can get <package-name>-<package-version>-arm.tar.xz output file.


4. Use `vdpm <package-name>-<package-version>-arm.tar.xz` to install package to VitaSDK.


## Thanks

* [vitasdk](https://github.com/vitasdk)
* [xfangfang](https://github.com/xfangfang "GitHub: xfangfang") - [wiliwili](https://github.com/xfangfang/wiliwili)