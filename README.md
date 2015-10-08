# React Native Emoji

Emoji as React Native component

```JSX
<Emoji type="coffee" style={{fontSize: 50}} />
```

![](http://i59.tinypic.com/fe3rly.png)

### Installation

1. Install package via npm:

```
npm install react-native-emoji
```

2. Require in your project

```javascript
var Emoji = require('react-native-emoji');
```

### Component properties
- `type` (String) - Emoji's name ([full list](http://unicodey.com/emoji-data/table.htm))
- `style` (Object) - Regular React styles for `Text` component

### Credits

Based on [node-emoji](https://github.com/omnidan/node-emoji).