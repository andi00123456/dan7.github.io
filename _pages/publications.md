---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
biliography: bibliography.bib
---
<!-- <link type ="text/css" rel = "stylesheet" href = "popUp.css"/> -->
<head>
<style> 
/* 弹窗 (background) */
.modal {
    display: none; /* 默认隐藏 */
    position: fixed; /* 固定定位 */
    z-index: 1; /* 设置在顶层 */
    left: 0;
    top: 0;
    width: 100%; 
    height: 100%;
    overflow: auto; 
    background-color: rgb(0,0,0); 
    background-color: rgba(0,0,0,0.4); 
}
/* 弹窗内容 */
.modal-content {
    background-color: #fefefe;
    margin: 15% auto; 
    padding: 20px;
    border: 1px solid #888;
    width: 80%; 
}
/* 关闭按钮 */
.close {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}
.close:hover,
.close:focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
}
</style>
<script >
// 获取弹窗
var modal = document.getElementById('myModal');
// 打开弹窗的按钮对象
var btn = document.getElementById("myBtn");
// 获取 <span> 元素，用于关闭弹窗
var span = document.querySelector('.close'); 
// 点击按钮打开弹窗
btn.onclick = function() {
    modal.style.display = "block";
} 
// 点击 <span> (x), 关闭弹窗
span.onclick = function() {
    modal.style.display = "none";
}
// 在用户点击其他地方时，关闭弹窗
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script> 
</head>

# Journal Publications
<table style="border: none; border-collapse: collapse;" border="0">

<tr style="border-collapse: separate; border-spacing:30em;">
<td style="border-collapse: collapse; border: none;">
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/FADE2Dmovie.gif" width="800"/>
</td>

<td style="border-collapse: collapse; border: none;">
<font size = "5"> Soil Methane Emission Suppression Control Using Unmanned Aircraft Vehicle Swarm Application of Biochar Mulch - A Simulation Study. Journal of Information and Intelligence, 2022. </font>
<br>
<font size = "3"> <b>Di An</b>, Derek Hollenbeck, Kai Cao, YangQuan Chen, <b>In press</b> </font>
<br>

<!-- <img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://arxiv.org/abs/1909.11895">arxiv paper</a></span>
<br> -->
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/github_icon.png" width="20" height="20" hspace="5">
<span><a href="https://github.com/andi00123456/FADE-MAS2D.git">code</a></span>
</td>
</tr>

<tr style="border-collapse: separate; border-spacing:30em;">
<td style="border-collapse: collapse; border: none;">
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/gnc1.png" width="800"/>
</td>

<td style="border-collapse: collapse; border: none;">
<font size = "5"> Spatial Path Tracking Controllers for Autonomous Ground Vehicles: Conventional and Nonconventional Schemes. Guidance, Navigation and Control, 2021. </font>
<br>  
<font size = "3"> Peng Wang, <b>Di An</b>, Ning Chen, YangQuan Chen </font>
<br>

<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://doi.org/10.1142/S2737480721500035">paper</a></span>
<br>
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/citation_icon.png" width="20" height="20" hspace="5" >
<!-- 打开弹窗按钮 -->
<button id="myBtn">打开弹窗1</button>

<!-- 弹窗 -->
<div id="myModal" class="modal">

  <!-- 弹窗内容 -->
  <div class="modal-content">
    <span class="close">&times;</span>
    <p>弹窗中的文本...</p>
  </div>

</div>
<!-- <span><a class="trigger_popup_fricc"> citation ></a>
<span class="hover_bkgr_fricc">
    <span class="helper"></span>
    <span>
        <span class="popupCloseButton">&times;</span>
        <p>@article{wang2021spatial,<br />
             title={Spatial path tracking controllers for autonomous ground vehicles: Conventional and nonconventional schemes},<br />
             author={Wang, Peng and An, Di and Chen, Ning and Chen, Yang Quan},<br />
             journal={Guidance, Navigation and Control},<br />
             volume={1},<br />
             number={01},<br />
             pages={2150003},<br />
             year={2021},<br />
             publisher={World Scientific}<br />
            }</p>
        </span>
    </span>
</span> -->
<!-- <head>
<meta name = "viewport" content="witdth=device-width, initial-scale=1">
<title> Popup Vanilla Javascript</title>
<link rel="stylesheet" type = "text/css" href="style.css">
</head>
<body>
    <div class="container">
     -->
<br>
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/github_icon.png" width="20" height="20" hspace="5">
<span><a href="https://github.com/njfuwp/nonconventional-PI-spatial-controller">code</a></span>
</td>
</tr>

</table>

# Conference Publications
<table style="border: none; border-collapse: collapse;" border="0">

<tr style="border-collapse: separate; border-spacing:30em;">
<td style="border-collapse: collapse; border: none;">
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/hardware.jpeg" width="800"/>
</td>

<td style="border-collapse: collapse; border: none;">
<font size = "5"> A Soil Carbon Content Quantification Method Using A Miniature Millimeter Wave Radar Sensor and Machine Learning. <b> IEEE/MESA, 2022.</b> </font>

<!-- <br>  change line -->
<br>
<font size = "3"> <b>Di An</b>, YangQuan Chen, <b>In press</b> </font>
<br>

<!-- <img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://doi.org/10.1117/12.2618728">paper</a></span>
<br> -->
</td>
</tr>

<tr style="border-collapse: separate; border-spacing:30em;">
<td style="border-collapse: collapse; border: none;">
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/ebikes.jpg" width="800"/>
</td>

<td style="border-collapse: collapse; border: none;">
Smart Bi-eBikes (SBB): a low cost UGV solution for precision agriculture applications. SPIE, 2022.
  
<b>Di An</b>, Haoyu Niu, Levi Williams, YangQuan Chen
<br>

<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://doi.org/10.1117/12.2618728">paper</a></span>
<br>
</td>
</tr>


<tr style="border-collapse: separate; border-spacing:30em;">
<td style="border-collapse: collapse; border: none;">
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/microwave.png" width="800"/>
</td>

<td style="border-collapse: collapse; border: none;">
	
A Non-intrusive Quantification Method for Biochar Water Retention Capacity Using A Portable Microwave Sensor and Machine Learning. ICCMA, 2021
  
<b>Di An</b>, Haoyu Niu, YangQuan Chen
<br>

<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://ieeexplore.ieee.org/abstract/document/9646210">paper</a></span>
<br>
</td>
</tr>

<tr style="border-collapse: separate; border-spacing:30em;">
<td style="border-collapse: collapse; border: none;">
<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/dtpi2021.png" width="800"/>
</td>

<td style="border-collapse: collapse; border: none;">
Digital Twin enabled methane emission abatement using networked mobile sensing and mobile actuation. DTPI, 2021
  
<b>Di An</b>, YangQuan Chen
<br>

<img src="https://raw.githubusercontent.com/andi00123456/andi00123456.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://ieeexplore.ieee.org/abstract/document/9540133">paper</a></span>
<br>
</td>
</tr>
</table>