---
layout:     post
title:      macOS install Flutter
subtitle:   macOs ပေါ်တွင် Flutter SDK သွင်းနည်း
date:       2019-04-10
author:     BY
header-img: img/flutter.jpg
catalog: true
tags:
    - macOS
    - Flutter
    - Dart
    - SDK
    - install
    - Guide
---
 **Flutter SDK** အား macOS တွင်ထည့်သွင်းနည်း အဆင့်ဆင့် 。

### Flutter SDK Download

```
cd ~/development
unzip ~/Downloads/flutter_macos_v1.12.13+hotfix.9-stable.zip
```

```
git clone https://github.com/flutter/flutter.git -b stable
```

```
export PATH="$PATH:`pwd`/flutter/bin"

```

```
flutter precache
```

```
flutter doctor
```



