<center><h1>Face Detection with OpenCV</h1></center>
<center><h4>Very simple tool for face detection on Image or Video</h4></center>
<h2>Services</h2>
<ul> 
<li>
<h3><b>ImageDetection</b></h3>
<ul>
<li>
<b>Instance Methods</b>
<ul>
<li>
    .show() show of detection result on window (<b>with your params</b>)
</li>
<li>
    .detect() write new file with detected faces (<b>with your params</b>)
</li>
</ul>
</li>
<li>
<b>Instance Attributes</b>
<ul> 
<li> 
<b>path</b>: path to file (.png, .jpeg, .jpg, ...) <i>REQUIRED</i>
</li>
<li>
<b>scale_factor</b>: (Read the OpenCV docs) <i>REQUIRED</i>
</li>
<li>
<b>min_neighbors</b> (Read the OpenCV docs) <i>REQUIRED</i>
</li>
<li>
<b>rect_color</b> color of rectangle (detected objects) must be tuple (B, G, R)
</li>
<li>
<b>text</b> title of detected objects
</li>
<li>
<b>text_color</b> color of text (detected objects) must be tuple (B, G, R)
</li>
<li>
<b>show_title</b>: title of detected objects window
</li>
<li>
<b>delay</b>: cv2.waitKey(delay)
</li>
<li>
<b>output_path</b>: if you call .detect() method, you must set result file path
</li>
</ul>
</li>
<li>
<h3><b>VideoDetection</b></h3>
<ul>

</ul>
</li>
</ul>
</li>
</ul>

<h2>Examples</h2>
<ul>
<li>
<h3><b>ImageDetection</b></h3>
<ul>
<li><b>.detect()</b></li>
<li><b>Before detection image</b></li>
<img src="static/images/img.png" alt=""/>
<li><b>After Face Detection image</b></li>
<img src="static/examples/detected_faces.png" alt="">
</ul>
</li>
</ul>