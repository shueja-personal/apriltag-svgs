These SVGS were generated from the PNGs provided by AprilRobotics. https://github.com/AprilRobotics/apriltag-imgs

The converter included is taken from https://codepen.io/shshaw/pen/XbxvNj?editors=0010 licensed under MIT by being public under CodePen terms.

Process:
1. Open /converter/index.html
1. Click "Choose File" and multi-select ten images. The site will automatically convert them to svg.

1. Copy this code into the browser console to download all ten svgs.

```javascript
var cusid_ele = document.getElementsByClassName('output');
for (var i = 0; i < cusid_ele.length; ++i) {
    var item = cusid_ele[i];  
    item.childNodes[0].click();
}
```
>The browser will likely ask permission to download multiple files, which should be granted.

## Notes:
 * Built in support for downloading all files may come soon.

