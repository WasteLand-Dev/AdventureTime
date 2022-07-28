# modpacksodium
```v9.2.7.46-Release```
```Stable```

### Changelog:
- Fix blending for the 1.19 version
- Re-order skyboxes by greatest alpha instead of time
- Fixed cape mod compatibility
- Added quark compatibility warning that disables incompatible features
- Add a warning screen when custom Microsoft auth URLs are in use
- Add traditional Chinese translation (AuthMe)
- Added many Optifine parity improvements:
 - Use overworld time in nether/end to match OptiFine behavior
 - Added at_midBlock support (This is a OptiFine attribute that measures the pixel relative to the middle of the block in 1/64 segments.)
 - Added support for the shadowInternalFormat, shadowClearColor, shadowClear const variables.
 - Added support for usampler2D and uimage2D samplers
 - Added support for 8 and 16 bit unsigned integer formats
 - Added full support for the clouds option
 - Added support for the sun and moon options
 - Handle basic disabling of programs
- Use lower Mixin priority in MixinClientLanguage to avoid issues with Spectrum 1.4.0
- Fixed ender beam effect in the End not animating with Complementary
- Avoided allocations in the shadow frustum calculation to improve shadow performance slightly.
- Use a version counter to reload Sodium shaders
- Fixed the entityColor geometry shader passthrough
- Modify block outline wrap function to be compatible with Create 0.5
- Preserve GUI render state when vignette is off
- Fix normals on the inside of flowing water
- Added firstPersonCamera bool uniform
- Updated Slovakian translation (Iris)
- Update shaders
- Disable chat encryption

```This modpack works on fabric!```
https://fabricmc.net/

[Site]: https://wlorigin.cf/
[Download]: https://wlorigin.cf/downloadmodpack.html
[Discord]: https://discord.gg/UBaauaN
[Telegram]: https://t.me/wlorigin

[Our site][Site] - [Download][Download] - [Our Discord][Discord] - [Our telegram channel (RU)][Telegram]

```
Совет: установите нашу иконку для установки в лаунчере (launcher_logo.png)
Совет: используйте эти параметры запуска, они помогут добиться большей эффективности :)
Совет: используйте последнюю версию fabric
```
```
Tip: install our icon to install in the launcher (launcher_logo.png)
Tip: use these launch options, they will help you to be more efficient :)
Tip: use the latest version of fabric
```

#### Launch options
```
-Xmx4096M -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=30 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=200 -XX:G1HeapRegionSize=8M -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -XX:+UseDynamicNumberOfGCThreads -XX:+AlwaysPreTouch -XX:+ParallelRefProcEnabled -XX:+UseInterpreter -XX:+RewriteFrequentPairs
```