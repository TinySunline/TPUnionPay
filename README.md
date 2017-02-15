# TPUnionPay

[![CI Status](http://img.shields.io/travis/kingdomrain/TPUnionPay.svg?style=flat)](https://travis-ci.org/kingdomrain/TPUnionPay)
[![Version](https://img.shields.io/cocoapods/v/TPUnionPay.svg?style=flat)](http://cocoapods.org/pods/TPUnionPay)
[![License](https://img.shields.io/cocoapods/l/TPUnionPay.svg?style=flat)](http://cocoapods.org/pods/TPUnionPay)
[![Platform](https://img.shields.io/cocoapods/p/TPUnionPay.svg?style=flat)](http://cocoapods.org/pods/TPUnionPay)

## Usage
    var union=new UnionPay();
    union.tn="201605031034241756648";
    union.success=function(data){
        log("success:"+data);
    }
    union.error=function(data){
        log("error:"+data);
    }
    union.pay();


## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

TPUnionPay is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "TPUnionPay"
```

## tips
官方帮助文档地址  
https://open.unionpay.com/ajweb/product/detail?id=3


## Author

kingdomrain, bygd2014@sina.com

## License

TPUnionPay is available under the MIT license. See the LICENSE file for more info.

