# rsschool-cv

# Eugene Robuk

### Frontend Developer
***

### Contact information: 

**Phone:** +7 (909)-539-94-16

**E-mail:** mistersmister66@gmail.com

**Telegram:** https://t.me/BJack70
***
### About me:

In the summer of 2021, the IT sector attracted my attention, until that moment I had not even thought about it. I started watching and reading a lot about IT, and then I firmly decided that I would become a programmer. But I didn't have a laptop, so after working all summer, by the end of August I was able to buy my first laptop. I really enjoyed working on the computer. And from that moment I started my web developer marathon. Maybe not very fast, but firmly, because I strive for it every day.

Although I had many moments before when I stopped learning to code and read again, so that the initial motivation was gone, because of this I did not feel very good. Now I understand that this was due to my wrong approach to learning, since I was alone and without a mentor.

After the new year 2023, I began to get acquainted on the Internet with people who are engaged in IT. Communicating with them helped me get back on the right track and put in twice as much effort. And now I will work every day until I reach my goal.
***

### Skills 
  * HTML, CSS
  * JavaScript
  * Git, GitHub
  * Webpack
  * Gulp
  * SASS(SCSS)
  * Bootstrap
***

### Code example:

**Which color is the brightest? KATA from CODEWARS:** One of the common ways of representing color is the RGB color model, in which the Red, Green, and Blue primary colors of light are added together in various ways to reproduce a broad array of colors. One of the ways to determine brightness of a color is to find the value V of the alternative HSV (Hue, Saturation, Value) color model. Value is defined as the largest component of a color. You are given a list of colors in 6-digit hexidecimal notation #RRGGBB. Return the brightest of these colors. If there are multiple brightest colors, return the first one.

```
function brightest(colors) {

 let index = 0
 let V = 0
 
 for(let i = 0; i < colors.length; i++) {
   const R = parseInt(colors[i].slice(1, 3), 16)
   const G = parseInt(colors[i].slice(3, 5), 16)
   const B = parseInt(colors[i].slice(5), 16)
   
   const currentV = Math.max(R, G, B)
   
   if(currentV > V) {
     V = currentV
     index = i
   }
  }
  
  return colors[index]
}
```
***
