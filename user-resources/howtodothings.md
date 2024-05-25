# How to do things <!-- omit from toc -->
- [Add a new icon to the taskbar](#add-a-new-icon-to-the-taskbar)
- [Import the taskbar into a new file](#import-the-taskbar-into-a-new-file)
- [Edit in codespaces](#edit-in-codespaces)

## Add a new icon to the taskbar
1.  Add a new `<a>` tag with the href attribute set to the path of the app.
2. Add an `<img>` tag with the src attribute set to the path of the app's icon.
3. Add the name of the app as the value of the NAME attribute of the `<a>` tag. THE IMPORTANT STEP 
ex: `<a name="blah" href="./path-to-file.html"><img href="./icon/path-to-image.jpg"></a>`

## Import the taskbar into a new file
1. At the bottom, add a new `<div>` with a class of taskbar (`<div class="taskbar">`)
2. At the top, add these two lines:
    - `<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>`
    - `<script src="./taskbar.js"></script>`

## Edit in codespaces
1. Click the green "`Code`" button
2. Click the `Codespaces` tab
3. Click the codespace avaliable (should be "`cuddly memory`")
4. Close the tab when done to reduce hours usage