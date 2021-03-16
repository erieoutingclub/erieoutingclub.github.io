---
layout: post
title: "Hiking Example"
---

title: "Hiking Example"


<table border="0" cellpadding="0">
  <caption><strong>Ride Turns Photos-Scroll Down and hit the Next button to view slide show</strong></caption>
  <tr>
    <td width="100%"><img src="https://i.imgur.com/x04PLZmh.jpg" width="960" height="720" class="responsive" name="photoslider"></td>
  </tr>
  <tr>
    <td width="100%"><form method="POST" name="rotater">
      <div align="center"><center><p><script language="JavaScript1.1">
var photos=new Array()
var which=0

/*Change the below variables to reference your own images. You may have as many images in the slider as you wish*/
photos[0]="https://i.imgur.com/x04PLZmh.jpg"
photos[1]="https://i.imgur.com/PQCgm0Ch.jpg"
photos[2]="https://i.imgur.com/JNgtPKfh.jpg"
photos[3]="https://i.imgur.com/1E3J2C4h.jpg"
photos[4]="https://i.imgur.com/UD8RSJsh.jpg"
photos[5]="https://i.imgur.com/jbXAKIvh.jpg"
photos[6]="https://i.imgur.com/AHbazCoh.jpg"
photos[7]="https://i.imgur.com/h3e3dAsh.jpg"
photos[8]="https://i.imgur.com/xdTLIqih.jpg"
photos[9]="https://i.imgur.com/n1dVCvlh.jpg"
photos[9]="https://i.imgur.com/MO5LAqgh.jpg"



function backward(){
if (which>0){
window.status=''
which--
document.images.photoslider.src=photos[which]
}
}

function forward(){
if (which<photos.length-1){
which++
document.images.photoslider.src=photos[which]
}
else window.status='End of gallery'
}
</script><input type="button" value="&lt;&lt;Back" name="B2"
      onClick="backward()"> <input type="button" value="Next&gt;&gt;" name="B1"
      onClick="forward()"><br>
      <a href="#" onClick="which=1;backward();return false"><small>Start Over</small></a></p>
      </center></div>
    </form>
    </td>
  </tr>
</table>

<p align="center"><font face="arial" size="-2">This free script provided by</font><br>
<font face="arial, helvetica" size="-2"><a href="http://javascriptkit.com">JavaScript
Kit</a></font></p>
<p>Pet Cememtary Ride. This ride start at Asbury Park on Asbury Road in Millcreek</p>


<p>View Ride on <a href="https://ridewithgps.com/routes/34137529">Ride By GPS</a></p>