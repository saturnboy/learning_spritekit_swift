# Learning SpriteKit with Swift

A few sample scenes exercising the different aspects of SpriteKit game dev in Swift.

**learning_spritekit** - simple example app to exercise SpriteKit, with some scenes:

* __GameScene__ - basic sprite motion and touch handling
* __GameScene2__ - fancy actions
* __GameScene3__ - hit testing and sound
* __GameScene4__ - texture animations
* __GameScene5__ - the full game

*NOTE: as of iOS 8.1.1, there are still two separate bugs with 3x image assets placed in a .atlas folder.  First, the compiled atlas image includes the 1x and 3x images in the 1x atlas, not in a separate 3x atlas image as is correct.  Second, even when using a a 3rd party tool like TexturePacker to correctly create the atlas images, the 3x assets are not used on the iPhone 6 Plus, instead the 2x images are used and scaled 1.5x.*
