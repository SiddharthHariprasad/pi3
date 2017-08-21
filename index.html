<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
<title>Monitor and Control</title>
</head>
<body>
<h2>VIEW</h2>
<div style="width:640px;">
<img id="view_image" alt="View being monitored" height="480" width="640" src="" />
<button type="button" id="img_btn" style="display: block; margin:auto;">Monitor</button>
</div>
<h2>Light Control</h2>
<p>
<button type="button" id="led_btn_1" data-led="1">Led 1 On</button>
<button type="button" id="led_btn_2" data-led="2">Led 2 On</button>
<button type="button" id="led_btn_3" data-led="3">Led 3 On</button>
</p>
<script>
var img = document.getElementById("view_image");
var img_btn = document.getElementById("img_btn");

var led_btn_1 = document.getElementById("led_btn_1"); 
var led_btn_2 = document.getElementById("led_btn_2"); 
var led_btn_3 = document.getElementById("led_btn_3"); 

img_btn.addEventListener("click", nextImage);

led_btn_1.addEventListener("click", onLedBtnClick);
led_btn_2.addEventListener("click", onLedBtnClick);
led_btn_3.addEventListener("click", onLedBtnClick);

function onLedBtnClick(event) {
  var target = event.target;
  var led_num = target.dataset.led;
  //console.log(target.innerText);
  if (target.innerText.endsWith("On")) {
    target.innerText = "Led " + led_num + " Off";
  } else {
    target.innerText = "Led " + led_num + " On";
  }
  target.disabled = true;
  fetch("/led/" + led_num).then(function(response) {
    target.disabled = false;
  });
}

function nextImage() {
  img_btn.disabled = true;
  fetch("/monitor").then(function(response) {
    return response.blob();
  }).then(function(blob) {
    var objectURL = URL.createObjectURL(blob);
    img.src = objectURL;
    img_btn.disabled = false;
    }).catch(function(error) {
    console.log("Error fetching");
    img_btn.disabled = false;
    });
}

</script>
</body>
</html>

