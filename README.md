## Welcome to <font color=crimson>San2 Art</font> Github Page

Hi, I am Santu Biswas, called by San2. My website [San2Art](https://www.san2.co.in/) . There are some tools to help in work.
This is my github [website](https://san2biswas.github.io/San2Art/).


## <font color=00BFFF>Nuke</font>

### **_<font color=F08080>S2 Toolset</font>_**



[S2_AutoCrop](https://github.com/San2biswas/San2Art/blob/main/S2_AutoCrop_1.nk)<br>
[S2_BlackWhite](https://github.com/San2biswas/San2Art/blob/main/S2_BlackWhite_1.nk)<br>
[S2_Clamp](https://github.com/San2biswas/San2Art/blob/main/S2_Clamp_1.nk)<br>
[S2_EdgeFusion](https://github.com/San2biswas/San2Art/blob/main/S2_EdgeFusion_1.nk)<br>
[S2_LWremoval](https://github.com/San2biswas/San2Art/blob/main/S2_LWremoval_1.nk)<br>
[S2_LightBlink](https://github.com/San2biswas/San2Art/blob/main/S2_LightBlink_1.nk)<br>
[S2_QCToolAlpha](https://github.com/San2biswas/San2Art/blob/main/S2_QCToolAlpha_1.nk)<br>
[S2_QCToolColor](https://github.com/San2biswas/San2Art/blob/main/S2_QCToolColor_1.nk)<br>
[S2_Sharpen](https://github.com/San2biswas/San2Art/blob/main/S2_Sharpen_1.nk)<br>
[S2_UseDisk](https://github.com/San2biswas/San2Art/blob/main/S2_UseDisk_1.nk)<br>



A set of tools are created by regular nuke nodes by grouping, mixxing and using programming languages. This nodes help to work faster and efficient.








<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: "Lato", sans-serif;}

/* Style the tab */
.tab {
  float: left;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
  width: 30%;
  height: 300px;
}

/* Style the buttons inside the tab */
.tab button {
  display: block;
  background-color: inherit;
  color: black;
  padding: 22px 16px;
  width: 100%;
  border: none;
  outline: none;
  text-align: left;
  cursor: pointer;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current "tab button" class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  float: left;
  padding: 0px 12px;
  border: 1px solid #ccc;
  width: 70%;
  border-left: none;
  height: 300px;
}
</style>
</head>
<body>

<h2>Vertical Tabs</h2>
<p>Click on the buttons inside the tabbed menu:</p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">London</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Paris</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Tokyo</button>
</div>

<div id="London" class="tabcontent">
  <h3>London</h3>
  <p>London is the capital city of England.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Paris</h3>
  <p>Paris is the capital of France.</p> 
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>













