These SVGS were generated from the PNGs provided by AprilRobotics. https://github.com/AprilRobotics/apriltag-imgs

The converter used was https://codepen.io/shshaw/pen/XbxvNj?editors=0010

Process:
Click "Choose File" and multi-select ten images. The site will automatically convert them to svg.

Copy this code into the browser console to download all ten svgs.

var cusid_ele = document.getElementsByClassName('output');
for (var i = 0; i < cusid_ele.length; ++i) {
    var item = cusid_ele[i];  
    item.childNodes[0].click();
}

The browser will likely ask permission to download multiple files, which should be granted.

