---
title: Gestures
description: Detect user interaction within your app
weight: 12
lastmod: 2019-07-13T10:13:30-04:00
draft: false
emoji: 🐦
vimeo: 336025234
---

## Example Code

{{< file "dart" "main.dart" >}}
{{< highlight dart >}}
//...
         child: GestureDetector(
           onTapDown: (details) => print(details.globalPosition.dx),
           child: Container(
             width: 100,
             height: 100,
             color: Colors.red
           ),
         ),
//...
{{< /highlight >}}