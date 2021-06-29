# Super Duper Crazily Clean Font That Is Super Awesome
(don't tell anbody but actually it came from Em.....shuuuuuuushhhhhhhhhh)

### What is the font?
"Nibus Sans D OT Light" is the font, and ***ohmygosh*** it's probobally the cleanest thing I have ever ever ever ever seen
There is an example over at my site [here](https://foreverpyrite.github.io/css/font-example.html)
You can't tell me this isn't awesome.

## Wait now how do **I** use it?
That's....a little tought BUT

Open up your CSS file (or make one and learn how to import stylesheets, it's extremely easy) and just copy and past this as your font face (@font-face)
```css
@font-face {
  font-family: 'nimbus_sans_d_otlight';
  src: url('https://foreverpyrite.github.io/css/font-files/nimbus-sans-d-ot-light_32752-webfont.woff2') format('woff2'),
       url('https://foreverpyrite.github.io/css/font-files/nimbus-sans-d-ot-light_32752-webfont.woff') format('woff');
  font-weight: normal;
  font-style: normal;

}
```
Now in any of your CSS atributes you want (even thought `@font-face` is defulting the font... or if you are using a varible of course. Then you are already smart enough to figure it out ;).)

For classes:
```css
.class-id-here{
    font-family: 'nimbus_sans_d_otlight';
}
```
For IDs:
```css
#element-id-here{
    font-family: 'nimbus_sans_d_otlight';
}
```
For basicly everything (with overwrite abilitys of course. @font-face should do this anyways like I said but whatever):
For classes:
```css
body{
    font-family: 'nimbus_sans_d_otlight';
}
```
You can see my stylesheet [here](https://foreverpyrite.github.io/css/stylesheet.css) for an example.

#### Want to download and host the files yourself?

Just return to the [main GitHub page](https://github.com/ForeverPyrite/Crazy-Clean-Font), click the green "`Code`" button, click  `Download ZIP`, extract the ZIP files however you can, and keep the `font-files` folder. That has all the needed files for this font.

Have your own font you want to use in your own website? First download whatever font you want, than head over to [FontSquirrel](https://www.fontsquirrel.com/tools/webfont-generator) and use your ginormus brain full of everything you just learned (If that wasn't enough you always have [Google](https://google.com) and [YouTube](https://youtube.com)).


##The .ttf file


If you want to use the Font for simpler things, like for your PC, than just go ahead and download the font file itself [right here](https://github.com/ForeverPyrite/Crazy-Clean-Font/blob/main/Nimbus-Sans-D-OT-Light_32752.ttf?raw=true)
