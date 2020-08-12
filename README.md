# Auto Swipe for Tinder, OkCupid and Bumble

#### Usage
1. Go to the website and press F12.
2. Copy and paste the corresponding script below and paste into your browser developer console.
3. Press `ENTER`.

### Tinder
```
setInterval( function () { var likeBtn = document.querySelector('[aria-label="Like"]'); likeBtn.click() }, 100)
```

### OkCupid
```
setInterval( function () { var likeBtn = document.querySelector('.doubletake-like-button'); likeBtn.click() }, 100)
```

### Bumble
```
setInterval( function () { var likeBtn = document.querySelector('.encounters-action--like'); likeBtn.click() }, 100)
```
