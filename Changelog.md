**September 19, 2019**
- Version 2.3
- Source code now available

**September 7, 2019**
- Version 2.2
- Added new project page

**March 13, 2019**
- Apk Utility v2.1
- New apktool.jar v2.4.0
- Java 8 (1.8) is now required.
- Updated baksmali/smali to version 2.2.6 (Issue 1893)
- Fixed issue with new restriction with non-empty ids.xml values. (Issue 1918) / Thanks gino247
- Fixed issue with PlatformBuildVersion properties changing to unexpected values. (Issue 1909) / Thanks gino247
- Fixed issue with pending v5 Gradle upgrade, by upgrading to gradle v4.10.2. (Issue 1943) / Thanks friederbluemle
- Added no-crunch support (optional) via new parameter of nc | --no-crunch. (Issue 1849) / Thanks Novex
- Fixed issue with xsd files decoding/building improperly between aapt1/aapt2. (Issue 1952)
- Fixed issue with malformed chunk header when decoding “special” apks. (Issue 1976) / Thanks sebras
- Fixed issue with Apktool stealing focus on Mac environments. (Issue 1996)
- Fixed issue with array resources having wrong types. (Issue 1994), (Issue 1922) / Thanks vbarthel-fr
- Fixed issue with 9patch images missing vertical or horizontal divs, by automatically creating them. (Issue 1522) / Thanks IgorEisberg
- Fixed issue with resolving references to non-standard framework files. / Thanks IgorEisberg
- Fixed issue with resolving SDK version codes were not explicit values. / Thanks IgorEisberg
- Added 32bit binaries for unix & windows for aapt and aapt2.
- Added automated tests on Windows. (Issue 1975)
- Added ability for api-level to be passed to baksmali & smali. / Thanks IgorEisberg

**November 7, 2018**
- Version 2.0
- Added support for android 9 pie

**June 7, 2018**
- Version 1.0
- First release
