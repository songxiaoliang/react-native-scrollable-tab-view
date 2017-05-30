
## react-native-scrollable-tab-view
### 基于原react-native-scrollable-tab-view库，对其进行扩展，添加tab间隔线。
#### 效果图：
<img src="http://oleeed73x.bkt.clouddn.com/4D08166E-5265-431A-A53C-414A7EAD9306.png">
以下是原库介绍：

This is probably my favorite navigation pattern on Android, I wish it
were more common on iOS! This is a very simple JavaScript-only
implementation of it for React Native. For more information about how
the animations behind this work, check out the Rebound section of the
[React Native Animation Guide](https://facebook.github.io/react-native/docs/animations.html)


## Add it to your project

1. Run `npm install react-native-scrollable-tab-view --save`
2. `var ScrollableTabView = require('react-native-scrollable-tab-view');`

## Demo
<a href="https://appetize.io/embed/6qfv7eydjtm34mhn6qwj2nt3xm?embed=true&screenOnly=false&xdocMsg=true&debug=true&scale=100&deviceColor=black&orientation=portrait&device=iphone6s&osVersion=9.3&deviceId=RGV2aWNlOjU2Y2FjNTExZWQwOTM2MTEwMGRhYTNlNg&platform=ios&width=375&height=668&phoneWidth=416&phoneHeight=870&screenOffsetLeft=21&screenOffsetTop=100&params=%7B%7D" target="_blank"><strong>Run this example</strong></a>

<a href="https://raw.githubusercontent.com/brentvatne/react-native-scrollable-tab-view/master/demo_images/demo.gif"><img src="https://raw.githubusercontent.com/brentvatne/react-native-scrollable-tab-view/master/demo_images/demo.gif" width="350"></a>
<a href="https://raw.githubusercontent.com/brentvatne/react-native-scrollable-tab-view/master/demo_images/demo-fb.gif"><img src="https://raw.githubusercontent.com/brentvatne/react-native-scrollable-tab-view/master/demo_images/demo-fb.gif" width="350"></a>

## Basic usage

```javascript
var ScrollableTabView = require('react-native-scrollable-tab-view');

var App = React.createClass({
  render() {
    return (
      <ScrollableTabView>
        <ReactPage tabLabel="React" />
        <FlowPage tabLabel="Flow" />
        <JestPage tabLabel="Jest" />
      </ScrollableTabView>
    );
  }
});
