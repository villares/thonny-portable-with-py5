# Portable Thonny IDE with py5 and some other libraries pre-installed

## Support my work!

[Donate any value](https://www.paypal.com/donate/?hosted_button_id=5B4MZ78C9J724)

## Thonny for Windows 64-bit

### 2025-10-28
[download](https://github.com/villares/thonny-portable-with-py5/releases/download/untagged-33b1dde2c4772cf9b317/thonny-4.1.7-windows-portable-py5-a107-050rc5.zip)
 Portable `Thonny 4.1.7` + with pre-installed py5:

```
  py5 0.10.7a0
  jpype 1.5.2 forced by downgrade
  thonny-py5mode 0.5.0rc5 (slightly modified)
```

**Note:** An experimental release using a modified version of thonny-py5mode 0.5.0rc5
 
### 2025-06-11

[download](https://github.com/villares/thonny-portable-with-py5/releases/download/2025-06-11/thonny-417-with-py5-0106a0-portable-r3.zip) Portable `Thonny 4.1.7` + with pre-installed py5:

```
  py5 0.10.6a0
  jpype 1.5.2
  numpy 2.1.3
  shapely 2.0.6
  trimesh 4.5.2
  pymunk 6.9.0
  scipy 1.14.1
```
**Notes:** 
- This includes the wonderful new helper [to install Processing community libraries](https://py5coding.org/how_tos/use_processing_libraries.html)!
- The "Manage packages" and "Manage plug-ins" panels broke on Thonny 4.1.6 and earlier versions due to recent changes in Python's PyPI infrastructure, but now Thonny 4.1.7 fixes these issues.
- Previous versions of the Thonny portable would break in a path containing non-ASCII characters (i.e. `C:\\Users\alê\Thonny-417-with-py5-portable\`). In theory the *jpype 1.5.2* release should fix that!

> Also note: I think I botched the previous releases with an outdated py5 version, sorry!
