# Super Duper Crazily Clean Font That Is Totally Awesome

### What is the font?
"Nibus Sans D OT Light" is the font, and ***ohmygosh*** it's probobally the cleanest thing I have ever ever ever ever seen
~~I'll try to get a demo link up sometime soon aka eventually and maybe never~~ 

## Wait now how do **I** use it?
That's....a little tough BUT

Open up your CSS file (or make one and learn how to import stylesheets, it's extremely easy and I'd be concerned if every single one of your pages used its own `<style>` tag) and just copy and past this as your font face (@font-face)
```css
@font-face {
  font-family: 'nimbus_sans_d_otlight';
  src: url('https://raw.githubusercontent.com/ForeverPyrite/Crazy-Clean-Font/main/font-files/nimbus-sans-d-ot-light_32752-webfont.woff2') format('woff2'),
       url('https://raw.githubusercontent.com/ForeverPyrite/Crazy-Clean-Font/main/font-files/nimbus-sans-d-ot-light_32752-webfont.woff') format('woff');
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

#### Want to download and host the files yourself?

<a href="https://github.com/ForeverPyrite/Crazy-Clean-Font/archive/refs/heads/main.zip" target="_blank">Click here</a>, extract the ZIP files however you prefer, and keep the `font-files` folder. That has all the needed files for this font.

Have your own font you want to use in your own website? First download whatever font you want as it's `.ttf file`, than head over to [FontSquirrel](https://www.fontsquirrel.com/tools/webfont-generator) and use your ginormous brain full of everything you just learned (If that wasn't enough you always have [Google](https://google.com) and [YouTube](https://youtube.com)).


## The .ttf file

If you want to use the Font for simpler things, like for your PC, than just go ahead and download the font file itself <a href="https://github.com/ForeverPyrite/Crazy-Clean-Font/blob/main/Nimbus-Sans-D-OT-Light_32752.ttf?raw=true" target="_blank">right here</a>
