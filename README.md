# MaterialCard

[![Version](https://img.shields.io/cocoapods/v/MaterialCard.svg?style=flat)](http://cocoapods.org/pods/MaterialCard)
[![License](https://img.shields.io/cocoapods/l/MaterialCard.svg?style=flat)](http://cocoapods.org/pods/MaterialCard)
[![Platform](https://img.shields.io/cocoapods/p/MaterialCard.svg?style=flat)](http://cocoapods.org/pods/MaterialCard)

An iOS CocoaPod that provides a MaterialCard class for creating Card Views based on the Material Design spec.

| Screenshot |
| :---: |
| ![Sample1](screenshots/1.png) |

## Installation

MaterialCard is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "MaterialCard"
```

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

```
let card = MaterialCard(frame: CGRectMake(10, UIApplication.sharedApplication().statusBarFrame.size.height + 10, UIApplication.sharedApplication().statusBarFrame.size.width - 20, 100))

let label = UILabel(frame: CGRectMake(0, 37, c.frame.size.width, 21))
label.textAlignment = NSTextAlignment.Center
label.text = "MaterialCard Demo"

card.backgroundColor = UIColor.whiteColor()
card.shadowOpacity = 0.2
card.shadowOffsetHeight = 0
card.cornerRadius = 0
card.addSubview(label)

self.view.addSubview(card)

```


## Author

Nathan Walker, walkerrunpdx@gmail.com

## License

MaterialCard is available under the MIT license. See the LICENSE file for more info.
