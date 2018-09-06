# statusBarWindow


``` swift

    func setStatusBarBackgroundColor(_ color: UIColor) {
        if let statusBar = (UIApplication.shared.value(forKey: "statusBarWindow") as? UIView)?.value(forKey: "statusBar") as? UIView {
//            let action = Selector.init("setBackgroundColor")
//            if statusBar.responds(to: action) {
                statusBar.backgroundColor = color
//            }
        }
    }

```
