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
![Hello](https://on.ahmda.ws/3dea3a3b1de3/c)

### 🙌 [THEDEVCOUPLE PARTNERS](https://TheDevCouple.com/partners)

This open source project is maintained by the help of awesome businesses listed below. What? [Read more about it →](https://TheDevCouple.com/partners)

<table width='100%'>
	<tr>
		<td width='500'><a target='_blank' href='https://kinsta.com/?kaid=WMDAKYHJLNJX&utm_source=TheDevCouple&utm_medium=Partner'><img src='https://on.ahmda.ws/73cedc/c' /></a></td>
		<td width='500'><a target='_blank' href='https://ahmda.ws/USES_WPE?utm_source=TheDevCouple&utm_medium=Partner'><img src='https://on.ahmda.ws/ff40fe/c' /></a></td>
	</tr>
	<tr>
		<td width='500'><a target='_blank' href='https://mythemeshop.com/?utm_source=TheDevCouple&utm_medium=Partner'><img src='https://on.ahmda.ws/3166d9/c' /></a></td>
		<td width='500'><a target='_blank' href='https://ipapi.com/?utm_source=TheDevCouple&utm_medium=Partner'><img src='https://d2ddoduugvun08.cloudfront.net/items/1R190r2U0p3N3L0U0b2u/ip-api.png'/></a></td>
	</tr>
</table>

<br />
<br />
<p align="center">
<strong>For anything else, tweet at <a href="https://twitter.com/MrAhmadAwais/" target="_blank" rel="noopener noreferrer">@MrAhmadAwais</a></strong>
</p>

<div align="center">
	<p>I have released a video course to help you become a better developer — <a href="https://VSCode.pro/?utm_source=GitHubFOSS" target="_blank">Become a VSCode Power User →</a></p>
    <br />
  <a href="https://VSCode.pro/?utm_source=GitHubFOSS" target="_blank">
  <img src="https://raw.githubusercontent.com/ahmadawais/shades-of-purple-vscode/master/images/vscodeproPlay.jpg" /><br>VSCode</a>

  _<small><a href="https://VSCode.pro/?utm_source=GitHubFOSS" target="_blank">VSCode Power User Course →</a></small>_
</div>

