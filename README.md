# Bach.playground
A simple playground to illustrate an issue with faded images

```swift
import UIKit
import PlaygroundSupport

//PlaygroundPage.current.needsIndefiniteExecution = true

let image = UIImage(named: "Johann_Sebastian_Bach.jpg")
```

If you comment/un-comment line 4, you'll see that the image is faded whenever the playground is still running.
Once you stop the playground, it appears as it should.
