---
layout: page
title: Photos
permalink: /photos/
---

<!-- <p>Created by <a target="_blank" href="http://html-tuts.com/">HTML-TUTS.com</a>. View full tutorial <a href="http://html-tuts.com/?p=2337" target="_blank">here</a>.</p> -->

<style type="text/css">
.thumbnails img {
	height: 80px;
	border: 4px solid #555;
	padding: 1px;
	margin: 0 10px 10px 0;
}

.thumbnails img:hover {
	border: 4px solid #00ccff;
	cursor:pointer;
}

.preview img {
	padding: 1px;
	width: 600px;
}
</style>

<div class="gallery" align="center">

	<div class="preview" align="center">
		<img name="preview" src="/assets/squat2015.jpg" alt=""/>
	</div>

	<div class="thumbnails">
		<img onmouseover="preview.src=img1.src" name="img1" src="/assets/squat2015.jpg" alt="Pledge Dinner 2015"/>
		<img onmouseover="preview.src=img2.src" name="img2" src="/assets/card.jpg" alt="XAM's business card"/>
	</div><br/>

</div>