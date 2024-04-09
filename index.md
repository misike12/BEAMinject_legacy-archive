---
layout: default
---
# BEAMinject

## :computer: Support
This only works on Windows,
and won't be ported to other platforms *(for obvious reasons)*.

For all support needed, you can open an issue!
And you can join our [Discord](https://dsc.gg/openm "OpenM Community") server
for further support needed.

## :rotating_light: About AV detections
Some poorly designed AVs *(namely Microsoft, Avast and AVG)* might detect our packed Python executables as a trojan.

There is [**nothing we can do about this**](https://github.com/pyinstaller/pyinstaller/issues/6754#issuecomment-1100821249) except sign the binaries, which is [***really* expensive**](https://codesigncert.com/blog/code-signing-certificate-cost).

Since the code is open and all builds are distributed via GitHub Actions, you can confirm that the executable is safe and whitelist it in your AV software!

## :page_with_curl: License
All code and assets are licensed under GNU AGPLv3.