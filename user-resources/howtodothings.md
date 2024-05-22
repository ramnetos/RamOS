# How to do things

## Add a new icon to the taskbar
1.  Add a new \<a\> tag with the href attribute set to the path of the app.
2. Add an \<img\> tag with the src attribute set to the path of the app's icon.
3. Add the name of the app as the value of the NAME attribute of the \<a\> tag. THE IMPORTANT STEP ex: \<a\ name="blah" href="./path-to-file.html">\<img href="./icon/path-to-image.jpg">\</a>

## Import the taskbar into a new file
1. At the bottom, add a new \<div> with a class of taskbar (\<div class="taskbar">)
2. At the top, add these two lines:
    - \<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    - \<script src="./taskbar.js"></script>
