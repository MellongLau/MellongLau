---
layout: post
title: "如何快速得到数组所有元素累加结果，平均值和最大最小值"
date: 2015-07-08 23:26:59 +0800
comments: true
categories: iOS
---

```objc
	NSArray *values = @[@72, @78, @75, @70, @72, @73, @77, @78, @75, @70, @72, @73, @87, @78, @75, @70, @72];
	NSNumber *avg = [values valueForKeyPath:@"@avg.self"];
	NSNumber *sum = [values valueForKeyPath:@"@sum.self"];
	NSNumber *max = [values valueForKeyPath:@"@max.self"];
    NSNumber *min = [values valueForKeyPath:@"@min.self"];
```

more:
https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/KeyValueCoding/Articles/CollectionOperators.html