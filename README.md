# Font-MonospacedDigits

Installation:
```Shell
git submodule add https://github.com/salutis/Font-MonospacedDigits.git
```

Usage:
```Swift
@IBOutlet private var timeLabel: UILabel! {
    didSet { 
        timeLabel.font = timeLabel.font.monospacedDigitFont 
    }
}
```
