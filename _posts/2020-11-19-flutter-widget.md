---
layout:     post
title:      Flutter Widget
subtitle:   Flutter Widget Guide
date:       2020-11-19
author:     Ko Htut
header-img: img/flutter_story.jpg
catalog: true
tags:
    - Flutter
    - Widget
    - Guide
    - Beginners
---
<h1 align="center">
  <a href="https://kohtut.dev/2020/11/19/flutter-wiget/"><img src="https://www.inovex.de/blog/wp-content/uploads/2019/01/Flutter-3.png" alt="KoHtut"></a>
</h1>

## OverflowBar

A widget that lays out its children in a row unless they "overflow" the available horizontal space, in which case it lays them out in a column instead.

This widget's width will expand to contain its children and the specified spacing until it overflows. The overflow column will consume all of the available width. The overflowAlignment defines how each child will be aligned within the overflow column and the overflowSpacing defines the gap between each child.

The order that the children appear in the horizontal layout is defined by the textDirection, just like the Row widget. If the layout overflows, then children's order within their column is specified by overflowDirection instead.

`spacing` : 
`overflowAlignment` :
`textDirection `:
`overflowSpacing` :
`overflowDirection` :
`clipBehavior`:

```dart
OverflowBar(
    spacing:5
    overflowAlignment: OverflowBarAlignment.end,
    children:<Widget>[
        Text("Hello 1"),
        Text("Hello 2"),
        Text("Hello 5"),
    ]
);
```