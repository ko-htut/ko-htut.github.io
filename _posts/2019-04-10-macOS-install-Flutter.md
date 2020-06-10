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
    - SDK
    - install
    - Guide
---
 **Flutter SDK** အား macOS တွင်ထည့်သွင်းနည်း အဆင့်ဆင့် 。

### System requirements ###

Flutter SDK ထည့်သွင်းရန် အောက်ပါတို့ကို အရင်ထည်သွင်းပေးဖို့လို အပ်ပါသည်..

- **Operating Systems** : macOS (64-bit)
- **Disk Space**: 2.8 GB (does not include disk space for IDE/tools).
- **Tools**: Flutter sdk ထည့်သွင်းဖို့ အောက်ပါ command-line tools များ ရှိမရှိကို ဦးစွာစစ်ဆေးပါ .
  - bash
  - curl
  - git 2.x
  - mkdir
  - rm
  - unzip
  - which
  - zip


### Get Started

**Flutter SDK** အား ထည့်သွင်းရန် Terminal တွင်အောက်ပါ command-line အား ရိုက်ထည့်၍  sdk အား ဦးစွာ Download ဆွဲချပါ .
```
cd ~/development
unzip ~/Downloads/flutter_macos_v1.12.13+hotfix.9-stable.zip
```

 **သို့မဟုတ်** .
```
git clone https://github.com/flutter/flutter.git -b stable
```
ဟုလည်း command-line အား ရိုက် ကာ sdk အား download ဆွဲ၍ ကိုယ်တိုင် zip ဖြေထားနိင်ပါသည် .


zip ဖြေထားသော Flutter SDK folder ကို Terminal ဖွင့်၍ Flutter sdk ကို အောက်ပါ comment line ဖြင့် run ပါ **( Termnal အားမပိတ်ပါနှင့် )**
```
export PATH="$PATH:`pwd`/flutter/bin"
```
ထိုသို့ run ပြီးသောအခါ Flutter ကို လက်ရှိ Terminal တွင် ယာယီ အသုံးပြုနိင်မည် ဖြစ်သည် ။

ဆက်လက်ပီး လက်ရှိ Terminal တွင်ပင် Flutter development ပြုလုပ်ရာတွင်လိုအပ်သော tool များကို Download ဆွဲပါမည် **flutter precache** comment line အားရိုက်၍ tool များအား download ဆွဲပါမည်..။
```
flutter precache
```
ပီးဆုံးသွားပါက Flutter pagckage များနှင့် Flutter dependencies များကျန်ရှိ ၊ မရှိကို **Flutter doctor** ဟုရိုက်၍ စစ်ဆေးနိင်ပါသည်။ flutter depencies များကျန်ရှိခြင်းမရှိပါက flutter ကိုအသုံးပြုရန််အတွက် ပြင်ဆင်ခြင်း ပြီးဆုံးပါပီ ။ **Terminal မှမထွက်ပါနှင့်**
```
flutter doctor
```
 ( ဆက်လက်၍ Flutter ကို အမြဲတမ်းအသုံးပြုနိင်ရန်် ၊ Flutter comment line tool များအား Terminal (zsh / Bash )မှသိရန်အတွက် Flutter sdk ပတ်လမ်းကို mainထဲသို့ ပြောင်းရွေ့ ကြပါမည် ။)


### Note
အကယ်၍ command ရိုက်ရာတွင် **bash: flutter: command not found** ဟုပေါ်လာပါက

```
bash: flutter: command not found
```
Flutter sdk ရှိရာ ပတ်လမ်းကြောင်းကို sudo paths ထဲတွင်ထည့်ပေးရပါမည်။
```
sudo nano /etc/paths
```
ဟု ရိုက်ပါ




