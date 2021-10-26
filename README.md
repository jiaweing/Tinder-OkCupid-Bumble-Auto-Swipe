# Auto Swipe for Tinder, OkCupid and Bumble

#### Usage
1. Go to the website and press F12.
2. Copy and paste the corresponding script below and paste into your browser developer console.
3. Press `ENTER`.

### Tinder
```
setInterval( function () { var likeBtn = document.querySelector('[class="button Lts($ls-s) Z(0) CenterAlign Mx(a) Cur(p) Tt(u) Bdrs(50%) P(0) Fw($semibold) focus-button-style Bxsh($bxsh-btn) Expand Trstf(e) Trsdu($normal) Wc($transform) Pe(a) Scale(1.1):h Scale(.9):a Bgc($c-like-green):a"]'); likeBtn.click() }, 100)
```

### OkCupid
```
setInterval( function () { var likeBtn = document.querySelector('.dt-action-buttons-button'); likeBtn.click() }, 100)
```
