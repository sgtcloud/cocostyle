csTypingLabel(extend cc.LabelTTF)
=========

### Quick Start

```
var tlabel = new csTypingLabel("My name is typing label!!!!!", "Arial", 30);
tlabel.setPosition(winSize.width / 2, winSize.height / 2);
this.addChild(tlabel);
tlabel.run(0.05);
```

### Fields

- {Number} _nowCur
- {String} _originalString
- And cc.LabelTTF fileds

### Methods

- `run(Number duration)`
- `stop()`
- `renew()`
- And cc.LabelTTF methods
- It's only work on HTML5.
