<table width='100%'>
    <tr>
        <td align='left' width='100%' colspan='2'>
            <strong>ReSass</strong><br />
            Sass SCSS Responsive Media Queries Mixin for Eight Different Screen Sizes! 💻📱🖥
        </td>
    </tr>
    <tr>
        <td>
            A FOSS (Free & Open Source Software) project. Maintained by <a href='https://github.com/ahmadawais'>@AhmadAwais</a>.
        </td>
        <td align='center'>
            <a href='https://AhmadAwais.com/'>
                <img src='https://i.imgur.com/Asg4d3k.png' width='100' />
            </a>
        </td>
    </tr>
</table>

## ⚡️  `ReSass`

![ReSass](https://github.com/ahmadawais/ReSass/raw/master/ReSass.jpg)


ReSass (`Re`sponsive`Sass`) creates responsive media queries for seven different screen sizes. These are based on min-width which means if x (x could be `240`, `320`, `480`, `768`, `1024`, `1140`, `1280`, or `1500`) is the size then your CSS will affect any device with screen width x and above.

#### USAGE:
![ReSass](https://github.com/ahmadawais/ReSass/raw/master/ReSass.gif)
CSS content goes inside {} brackets. These mixins should be used inside a class definition. 

```css
 @include r(240)  { }
 @include r(320)  { }
 @include r(480)  { }
 @include r(768)  { }
 @include r(1024) { }
 @include r(1140) { }
 @include r(1280) { }
 @include r(1500) { }
```

**For example:**
The following CSS will hide the .header on screen width 320px and above.
```css

.header {
   @include r(320)  { display: none; }
}
```

## ⚡️ Getting Started

Getting started is very easy. 

1. Download the raw [`resass.scss`](https://git.io/resass)
2. Import the [`resass.scss`](/resass.scss) in your main .SCSS file → `@import "path/to/resass";`
3. Now use any or all of the mixins inside a class' CSS.
4. Here's a fun [implementation at CodePen →](https://codepen.io/ahmadawais/full/eEzpgo/)

## ⚡️ License

MIT licensed. Content is copyright of AhmadAwais.com



---
### 🙌 [WPCOUPLE PARTNERS](https://WPCouple.com/partners):
This open source project is maintained by the help of awesome businesses listed below. What? [Read more about it →](https://WPCouple.com/partners)

<table width='100%'>
    <tr>
        <td width='225'><a target='_blank' href='https://www.gravityforms.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtrE/c' /></a></td>
        <td width='225'><a target='_blank' href='https://kinsta.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu5O/c' /></a></td>
        <td width='225'><a target='_blank' href='https://wpengine.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mto3/c' /></a></td>
        <td width='225'><a target='_blank' href='https://www.sitelock.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtyZ/c' /></a></td>
    </tr>
    <tr>
        <td width='225'><a target='_blank' href='https://wp-rocket.me/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtrv/c' /></a></td>
        <td width='225'><a target='_blank' href='https://blogvault.net/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtph/c' /></a></td>
        <td width='225'><a target='_blank' href='http://cridio.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtmy/c' /></a></td>
        <td width='225'><a target='_blank' href='http://wecobble.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtrW/c' /></a></td>
    </tr>
    <tr>
        <td width='225'><a target='_blank' href='https://www.cloudways.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu0C/c' /></a></td>
        <td width='225'><a target='_blank' href='https://www.cozmoslabs.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu9W/c' /></a></td>
        <td width='225'><a target='_blank' href='https://wpgeodirectory.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtwv/c' /></a></td>
        <td width='225'><a target='_blank' href='https://www.wpsecurityauditlog.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtkh/c' /></a></td>
    </tr>
    <tr>
        <td width='225'><a target='_blank' href='https://www.liquidweb.com//?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtnt/c' /></a></td>
        <td width='225'><a target='_blank' href='https://WPCouple.com/contact?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu3F/c' /></a></td>
        <td width='225'><a target='_blank' href='https://WPCouple.com/contact?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu3F/c' /></a></td>
        <td width='225'><a target='_blank' href='https://WPCouple.com/contact?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu3F/c' /></a></td>
    </tr>
</table>

