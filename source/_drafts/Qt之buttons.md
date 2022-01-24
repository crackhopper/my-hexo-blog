---
title: Qt之buttons
date: 2022-01-18 15:14:57
tags:
---

### QDialogButtonBox
可以容纳按钮的widget，可以让按钮以正确的形式在各个平台上展示。

单击一个带AcceptRole的按钮时，会发射accept()信号。同理还定义了RejectRole和CancelRole。在qtcreator中的体现就是定义在standardButtons内。