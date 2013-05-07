HTGraphics
==========

#### HTGraphics is a set of tools for drawing custom UI elements, including:

* HTHighlightedShapeView - Add a highlight effect to arbitrary UIBezierPaths
* HTRadialGradientView - Highly customizable radial gradient view
* HTShapeView - UIView wrapper around CAShapeLayer
* HTGraphicsUtilities.h contains useful functions like:

```objc
HTPointAtAngleAndDistanceFromPoint(CGPoint fromPoint, CGFloat angle, CGFloat distance)
HTCenterSizeInRect(CGSize size, CGRect rect)
HTSizeInset(CGSize size, CGFloat xInset, CGFloat yInset)
HTSizeEdgeInset(CGSize size, UIEdgeInsets edgeInsets)
HTSizeScale(CGSize size, CGFloat scale)
HTRectGrowSide(CGRect rect, CGRectEdge edge, CGFloat distance)
```

HTHighlightedShapeView and HTRadialGradientView can be rasterized using HTRasterView.

## Demo

See demo in https://github.com/hoteltonight/HTKit

## Installation

The recommended installation method is cocoapods. Add this line to your Podfile:

    pod 'HTGraphics'

http://cocoapods.org

HTRasterView is a dependency for those who don't cocoapods.

## Contributions welcome!

## Use it? Love/hate it?

Tweet the authors @jakejennings, @raylillywhite and @jonsibs, and check out HotelTonight's engineering blog: http://engineering.hoteltonight.com

Also, check out HotelTonight's other iOS open source:
* https://github.com/hoteltonight/HTAutocompleteTextField
* https://github.com/hoteltonight/HTRasterView
* https://github.com/hoteltonight/HTKit
* https://github.com/hoteltonight/HTGradientEasing
* https://github.com/hoteltonight/HTDelegateProxy
* https://github.com/hoteltonight/HTCoreImage
