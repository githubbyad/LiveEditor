# LiveEditor

### Script to place before `</body>` tag

`<link type="text/css" rel="stylesheet" href="{{PutHName}}/ufields.css" />`

`<script type="text/javascript" src="{{PutHName}}/ufields.js"></script>`

### Add `id=blbodymain` in `<body>` tag

### Issue with Editor Area on Hover?
- Sometimes, editor area is not showing in proper size due to that block's placement.
- Here, you need to place Attribute data-block="d-block p-relative f-left" in target block.
- Here, you can add following values separated by space.
   `d-inline` or `d-block`
   `p-relative` or `p-absolute`
   `f-left` or `f-right`
- Normally, we are not placing required display, float and position values while designing site.
NOTE : Make sure to use proper value here as per the target block.
- For example, if it require to place position:absolute, then you should use `p-absolute` value instead of `p-relative`.
  <img scr="https://raw.githubusercontent.com/githubbyad/Homepage-Editor/main/screenshots/block.png">
