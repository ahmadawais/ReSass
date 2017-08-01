<table width='100%'>
    <tr>
        <td align='left' width='100%' colspan='2'>
            <strong>ReSass</strong><br />
            💻📱🖥 Sass SCSS Responsive Media Queries Mixin for Eight Different Screen Sizes!
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

## ⚡️ What Is `ReSass`?

ReSass creates responsive media queries for seven different screen sizes. These are based on min-width which means if x (x could be `240`, `320`, `480`, `768`, `1024`, `1140`, `1280`, or `1500`) is the size then your CSS will affect any device with screen width x and above.

#### USAGE:
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

## ⚡️ License

MIT licensed. Content is copyright of AhmadAwais.com


